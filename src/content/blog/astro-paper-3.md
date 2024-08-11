---
author: Sat Naing
pubDatetime: 2023-09-25T10:25:54.547Z
title: AstroPaper 3.0
slug: astro-paper-v3
featured: false
ogImage: https://github.com/satnaing/astro-paper/assets/53733092/1ef0cf03-8137-4d67-ac81-84a032119e3a
tags:
  - release
description: "AstroPaper Version 3: 使用 Astro v3和无缝视图转换提升您的 Web 体验"
---

We're excited to announce the release of AstroPaper v3, packed with new features, enhancements, and bug fixes to elevate your web development experience. Let's dive into the highlights of this release:

![AstroPaper v3](@assets/images/AstroPaper-v3.png)

## 表格内容

## 功能和改变

### Astro v3 整合

<video autoplay loop="loop" muted="muted" plays-inline="true">
  <source src="https://github.com/satnaing/astro-paper/assets/53733092/18fdb604-1ca3-41a0-8372-1367759091ff" type="video/mp4">
  <!-- <source src="/assets/docs/astro-paper-v3-view-transitions-demo.mp4" type="video/mp4"> -->
</video>

AstroPaper 现在完全支持[ Astro v3]( https://Astro.build/blog/Astro-3/) ，提供了更好的性能和渲染速度。

除此之外，我们还增加了对 Astro 的视图转换 API ( https://docs.Astro.build/en/guides/view-transitions/)的支持，允许你在视图之间创建迷人的动态转换。

在“最近的部分”，只有非特色的文章将显示，以避免重复和更好地支持视图转换 API。

### 更新 OG 图像生成逻辑

![Example OG Image](https://user-images.githubusercontent.com/40914272/269252964-a0dc6735-80f7-41ed-8e74-4d4d70f96891.png)


我们更新了 OG 图像自动生成的逻辑，使其更加可靠和高效。此外，它现在支持在帖子标题中的特殊字符，确保准确、灵活和引人注目的社交媒体预览。

`SITE.ogImage` is now optional. If it is not specified, AstroPaper will automatically generate an OG image using `SITE.title`, `SITE.desc` and `SITE.website`

### 主题元标签

添加了主题颜色元标记，以动态适应主题切换，确保无缝用户体验。

> Notice the difference at the top

**_AstroPaper v2 theme switch_**

<video autoplay loop="loop" muted="muted" plays-inline="true">
  <source src="https://github.com/satnaing/astro-paper/assets/53733092/3ab5a1e8-1891-4264-a5bb-0ded69143c1a" type="video/mp4">
</video>

**_AstroPaper v3 theme switch_**

<video autoplay loop="loop" muted="muted" plays-inline="true">
  <source src="https://github.com/satnaing/astro-paper/assets/53733092/8ac9deb8-d1f8-4029-86bd-6aa0def380b4" type="video/mp4">
</video>

## Other Changes

### Astro Prettier Plugin

Astro Prettier Plugin is installed out-of-the-box in order to keep the project tidy and organized.

### Minor Style Changes

The single-line code block wrapping issue has been solved, making your code snippets look pristine.

Update nav style CSS to allow adding more nav links to the navigation.

## Upgrade to AstroPaper v3

> This section is only for those who want to upgrade AstroPaper v3 from the older versions.

This section will help you migrate from AstroPaper v2 to AstroPaper v3.

Before reading the rest of the section, you might also want to check [this article](https://astro-paper.pages.dev/posts/how-to-update-dependencies/) for upgrading dependencies and AstroPaper.

## Option 1: Fresh Restart (recommended)

In this release, a lot of changes have been made\_ replacing old Astro APIs with newer APIs, bug fixes, new features etc. Thus, if you are someone who didn't make customization very much, you should follow this approach.

**_Step 1: Keep all your updated files_**

It's important to keep all the files which have been already updated. These files include

- `/src/config.ts` (didn't touch in v3)
- `/src/styles/base.css` (minor changes in v3; mentioned below)
- `/src/assets/` (didn't touch in v3)
- `/public/assets/` (didn't touch in v3)
- `/content/blog/` (it's your blog content directory 🤷🏻‍♂️)
- Any other customizations you've made.

```css
/* file: /src/styles/base.css */
@layer base {
  /* Other Codes */
  ::-webkit-scrollbar-thumb:hover {
    @apply bg-skin-card-muted;
  }

  /* Old code
  code {
    white-space: pre;
    overflow: scroll;
  } 
  */

  /* New code */
  code,
  blockquote {
    word-wrap: break-word;
  }
  pre > code {
    white-space: pre;
  }
}

@layer components {
  /* other codes */
}
```

**_Step 1: Replace everything else with AstroPaper v3_**

In this step, replace everything\_ except above files/directories (plus your customized files/directories)\_ with AstroPaper v3.

**_Step 3: Schema Updates_**

Keep in mind that `/src/content/_schemas.ts` has been replaced with `/src/content/config.ts`.

Besides, there is no longer `BlogFrontmatter` type exported from `/src/content/config.ts`.

Therefore, all the `BlogFrontmatter` type inside files need to be updated with `CollectionEntry<"blog">["data"]`.

For example: `src/components/Card.tsx`

```ts
// AstroPaper v2
import type { BlogFrontmatter } from "@content/_schemas";

export interface Props {
  href?: string;
  frontmatter: BlogFrontmatter;
  secHeading?: boolean;
}
```

```ts
// AstroPaper v3
import type { CollectionEntry } from "astro:content";

export interface Props {
  href?: string;
  frontmatter: CollectionEntry<"blog">["data"];
  secHeading?: boolean;
}
```

## Option 2: Upgrade using Git

This approach is not recommended for most users. You should do the "Option 1" if you can. Only do this if you know how to resolve merge conflicts and you know what you're doing.

Actually, I've already written a blog post for this case and you can check out [here](https://astro-paper.pages.dev/posts/how-to-update-dependencies/#updating-astropaper-using-git).

## Outro

Ready to explore the exciting new features and improvements in AstroPaper v3? Start [using AstroPaper](https://github.com/satnaing/astro-paper) now.

For other bug fixes and integration updates, check out the [release notes](https://github.com/satnaing/astro-paper/releases/tag/v3.0.0) to learn more.

If you encounter any bugs or face difficulties during the upgrade process, please feel free to open an issue or start a discussion on [GitHub](https://github.com/satnaing/astro-paper).
