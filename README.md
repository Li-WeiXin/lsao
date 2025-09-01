# lsao

**Welcome to lsao's Cabin!**

[English](#english) | [中文](#中文)

<div id="english">

## English

lsao provides a resting spot for programmers, mainly including:

- Article sharing
- Technical sharing
- Technical communication

Visit my blog: [li-weixin.github.io](https://li-weixin.github.io)

lsao not only contains knowledge sharing and articles, but you can also directly visit the blog address above for more information.

In addition, lsao also has a series of derivative packages, forming a complete ecosystem:

### Packages

#### @lsao/core

Core SDK package, providing basic functions and shared tools.

#### @lsao/git-shared

Git-shared SDK package, built on the core package, providing git-shared-specific functions.

#### @lsao/cli

Scaffolding CLI tool for quickly creating and managing lsao projects.

### Management approach

This project is managed using pnpm + lerna:

- pnpm for dependency management and workspace support
- lerna for package version management and release process

### Common commands

```bash
# Install dependencies
pnpm install

# Add new dependencies to a package
lerna add <package> --scope=<target-package>

# Run commands in all packages
lerna run <script-name>

# Publish packages
lerna publish

```
</div>

<div id="中文">

## 中文

lsao 为程序员提供了一个休憩的港湾，主要包括：

- 文章分享
- 技术分享
- 技术交流

访问我的博客：[li-weixin.github.io](https://li-weixin.github.io)

lsao 不仅包含了知识分享和文章内容，也可以直接访问上述 blog 地址获取更多信息。

除此以外，lsao 还有一系列衍生包，形成了一个完整的生态系统：

## Packages

### @lsao/core

核心 SDK 包，提供基础功能和共享工具。

### @lsao/git-shared

git-shared SDK 包，基于核心包构建，提供 git-shared 相关功能。

### @lsao/cli

脚手架 CLI 工具，用于快速创建和管理 lsao 项目。

## 管理方式

本项目使用 pnpm + lerna 进行管理：

- pnpm 用于依赖管理和工作空间支持
- lerna 用于包版本管理和发布流程

## 常用命令

```bash
# 安装依赖
pnpm install

# 添加新的依赖到某个包
lerna add <package> --scope=<target-package>

# 在所有包中运行命令
lerna run <script-name>

# 发布包
lerna publish
```

</div>
