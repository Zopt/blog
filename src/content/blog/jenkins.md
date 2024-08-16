---
author: muyi
pubDatetime: 2024-08-15T15:22:00Z
modDatetime: 2024-08-15T09:12:47.400Z
title: Jenkins
slug: "jenkins"
featured: true
draft: false
tags:
  - docs
  - jenkins
description:
  VPN（虚拟私人网络）是一种可以在公共网络上建立加密通道的技术，通过这种技术可以使远程用户访问公司内部网络资源时，实现安全的连接和数据传输。
---

# Jenkins

Jenkins是一个开源的**持续集成**（Continuous Integration，CI）和**持续交付**（Continuous Delivery，CD）工具，它由Java编写，支持通过插件来扩展功能。自2004年发布以来，Jenkins已经成为业界最流行的CI/CD工具之一。以下是关于Jenkins的相关信息：
### Jenkins简介

Jenkins最初被称作Hudson，是一个用Java语言编写的开源的持续集成工具。它的用户界面非常简单直观，增加了视觉上的吸引力，而且Jenkins作为一个整体，具有平滑的学习曲线。Jenkins拥有良好的扩展性，能够极其灵活和方便地迎合你的想法。它有数以百计的开源插件可供使用，而且每周会有更多的开源插件贡献进来。这些开源插件覆盖系统版本控制、构建工具、构建通知、外部系统集成、用户界面定制化等。而且这些插件的安装都非常快捷和简单。具有活跃的开源社区，得益于其开源社区的规模和活跃度。
### Jenkins的主要功能

- **持续集成与持续交付**：自动化构建、测试和部署流程。
- **分布式构建**：支持将构建任务分发到多个节点上运行。
- **插件生态系统**：通过插件集成各种工具和服务，如版本控制系统、构建工具、测试框架、部署工具等。
- **可扩展性与灵活性**：适应各种规模和复杂度的项目，通过配置和自定义创建复杂的CI/CD流水线。
- **强大的社区支持**：丰富的社区资源、文档和支持。
### Jenkins的用途

Jenkins广泛应用于各种软件项目，包括Web应用程序、移动应用程序、嵌入式系统等。通过使用Jenkins，开发团队可以加快软件交付速度、提高质量，并促进团队协作和持续改进的文化。

### Jenkins在DevOps中的作用

Jenkins是DevOps实践中的一个重要工具，它在实现DevOps流程中扮演着关键的角色。通过持续集成、持续交付、自动化构建和测试、分布式构建和部署、监控和报告等实践，Jenkins帮助团队实现了DevOps的核心原则：加快软件交付速度、提高质量和稳定性、促进团队协作。

### Jenkins的安装与配置

Jenkins可以通过系统包、Docker或者通过一个独立的Java程序运行。安装和配置Jenkins涉及设置主节点和代理节点，配置网络权限，以及安装必要的插件。Jenkins的配置主要通过其Web界面进行，包括定义作业、代理节点、插件管理等。

### Jenkins的社区与支持

Jenkins拥有庞大的用户社区和广泛的用户基础。社区资源包括文档、论坛、邮件列表等，用户可以通过这些渠道获取帮助、交流经验并共享插件和解决方案。Jenkins社区的发展速度非常快，每周都会有新功能、新特性，以及bug修复和插件更新发布出来。

要安装Jenkins，您可以选择以下几种方法：

### 通过系统包管理器安装

对于基于Debian的系统（如Ubuntu），可以使用以下命令：

```bash
sudo apt-get update
sudo apt-get install jenkins
```

对于基于Red Hat的系统（如CentOS），可以使用以下命令：

```bash
sudo yum install epel-release
sudo yum install jenkins
```

### 通过Docker安装

如果您已经安装了Docker，可以使用以下命令来运行Jenkins容器：

```bash
docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts
```

这将在本地主机的8080端口上启动Jenkins Web界面。

### 通过Java可执行文件安装

首先，从Jenkins官方网站下载最新的WAR文件：

```bash
wget http://mirrors.jenkins.io/war-stable/latest/jenkins.war
```

然后，使用Java运行此WAR文件：

```bash
java -jar jenkins.war
```

默认情况下，Jenkins将在本地主机的8080端口上启动。

### 安装完成后

无论您选择哪种安装方法，都需要按照以下步骤完成Jenkins的初始设置：

1. 打开浏览器，访问`http://localhost:8080`（或者您选择的端口）。
2. 按照屏幕上的指示完成初始设置，包括解锁Jenkins、安装推荐的插件和创建第一个管理员用户。
3. 完成设置后，您可以登录到Jenkins并开始配置您的CI/CD流水线。

### 配置防火墙和端口

如果您的系统启用了防火墙，请确保允许访问Jenkins所需的端口（默认为8080）。对于基于Debian的系统，可以使用以下命令：

```bash
sudo ufw allow 8080
```

对于基于Red Hat的系统，可以使用以下命令：

```bash
sudo firewall-cmd --permanent --add-port=8080/tcp
sudo firewall-cmd --reload
```

现在，您已经成功安装并配置了Jenkins，可以开始使用它来自动化您的构建、测试和部署流程了。


