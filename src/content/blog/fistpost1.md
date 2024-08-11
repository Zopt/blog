---
author: muyi
pubDatetime: 2024-08-11T15:22:00Z
modDatetime: 2024-08-11T09:12:47.400Z
title: 第一篇中文博客
slug: 第一篇中文博客
featured: true
draft: false
tags:
  - docs
  - 博客
description:
    我们总是要开始做些什么，然后往那个反向继续走下去.
---

说话之前总是需要想好再说，需要注意点什么?

然后重新提交`git push origin main main`

然后报错

### 问题2

> fatal: unable to access 'https://github.com…………': Failed to connect to github.com port 443 after 21077 ms: Couldn't connect to server

1. 解决

```
git config --global --unset http.proxy
git config --global --unset https.proxy
```

### 问题3

> fatal: unable to access 'https://github.com…………': OpenSSL SSL_read: SSL_ERROR_SYSCALL, errno 0

解决：参考网上方法：解除SSL认证

```
git config --global http.sslVerify "false"
```

然后还是出现了

> fatal: unable to access 'https://github.com…………: Failed to connect to github.com port 443 after 21077 ms: Couldn't connect to server

可能因为科学上网了，关闭之后

>  ! [rejected]        main -> main (non-fast-forward)
>  error: failed to push some refs to 'https://github.com/…………
>  hint: Updates were rejected because the tip of your current branch is behind
>  hint: its remote counterpart. If you want to integrate the remote changes,
>  hint: use 'git pull' before pushing again.
>  hint: See the 'Note about fast-forwards' in 'git push --help' for details.

解决方法

```git
git pull origin master --allow-unrelated-histories
```





### 删除github的仓库

> 网上的文章有说`github`的仓库删除，还是会被保留文件，所以建议还是不要把太过机密的信息提交到`github`上，或者还有其他相关的方法。

1. 找到想要删除的仓库的位置，在project的上方的导航栏，最左边显示的是code,最后一个就是settings

![image-20240811115809577](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240811115809577.png)

2. 点击setting，然后下拉到最后，就可以看到删除仓库的操作了。

![image-20240811115955699](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240811115955699.png)

3. 然后按照流程走就行，这个比较简单，记得要输入`密码`，所以提前准备好密码，如果你能够记住最好啦。

> 如果你联系输入两个仓库，第一次输入密码之后，第二次删除就不需要输入密码了。



vercel的项目删除，在项目的settings 中，也是在最后

### github新创建本地仓库的操作

![image-20240811140535179](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240811140535179.png)

```BAHS
https://github.com/Zopt/blog.git

git@github.com:Zopt/blog.git
```





```bash
echo "# blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Zopt/blog.git
git push -u origin main
```

### …or push an existing repository from the command line

```BASH
git remote add origin git@github.com:Zopt/blog.git
git branch -M main
git push -u origin main
```

```bash
## error: remote origin already exists.
git remote rm origin
```

然后遇到

> git@github.com: Permission denied (publickey). Could not read from remote repository

解决：：https://blog.csdn.net/u013250861/article/details/130761369

具体：

> 原因分析
> Permission denied (publickey) 没有权限的publickey ，出现这错误一般是以下两种原因
>
> 客户端与服务端未生成 ssh key
> 客户端与服务端的ssh key不匹配
> 找到问题的原因了，解决办法也就有了，重新生成一次ssh key ，服务端也重新配置一次即可。
>
> 客户端生成ssh key
> ssh-keygen -t rsa -C "470812087@qq.com"
> 470812087@qq.com改为自己的邮箱即可，途中会让你输入密码啥的，不需要管，一路回车即可，会生成你的ssh key。（如果重新生成的话会覆盖之前的ssh key。）
>
>
>
> 然后再终端下执行命令：
>
> ssh -v git@github.com
>
>
> 最后两句会出现
>
> 　　No more authentication methods to try.
>
> 　　Permission denied (publickey).
>
>

然后到 ssh-agent -s 出现问题 在`bash`中操作

> unable to start ssh-agent service, error :1058

解决：https://blog.csdn.net/weixin_39370315/article/details/133440677

在powershell中操作，解决

继续

在操作

```bash
ssh-add ~/.ssh/id_rsa
~/.ssh/id_rsa: No such file or directory  ##报错

## 解决 该路径C:\Users\Administrator/.ssh/id_rsa
## 上面的PS  ssh-keygen -t rsa -C "youremail"
## Generating public/private rsa key pair.
## Enter file in which to save the key (`C:\Users\Administrator/.ssh/id_rsa`):
```

显示了密钥存储的路径为：C:\Users\Administrator/.ssh/id_rsa

所以命令改为

```bash
ssh-add C:\Users\Administrator/.ssh/id_rsa
Identity added: C:\Users\Administrator/.ssh/id_rsa (youremail.com) ##回复 成功
```

> 相关的问题：因为不是管理员权限的问题
>
> $ ssh-add ~/.ssh/id_rsa
> 出现Could not open a connection to your authentication agent.
> 这时可以使用：ssh-agent bash 命令，然后再次使用ssh-add ~/.ssh/id_rsa_name这个命令就没问题了。
> ——————————————
>
> 原文链接：https://blog.csdn.net/u013250861/article/details/130761369

拷贝C:\Users\Administrator/.ssh/路径下的 id_rsa.pub 文件中的密钥信息，就是一堆字母数字：以开头ssh-rsa 以你的邮箱结尾

在github的账户的settings 的SSH and GPG keys 中添加 New SSH key ，然后输入密码，添加成功。

![image-20240811151113145](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240811151113145.png)

- 添加成功，github 的导航栏下方提示

![image-20240811151529933](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20240811151529933.png)

- 电脑端验证：

验证ssh -T git@github.com
Hi yourgithubNickName! You've successfully authenticated, but GitHub does not provide shell access.

