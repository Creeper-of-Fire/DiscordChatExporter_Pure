# DiscordChatExporter

[![Status](https://img.shields.io/badge/status-maintenance-ffd700.svg)](https://github.com/Tyrrrz/.github/blob/master/docs/project-status.md)
[![Build](https://img.shields.io/github/actions/workflow/status/Tyrrrz/DiscordChatExporter/main.yml?branch=master)](https://github.com/Tyrrrz/DiscordChatExporter/actions)
[![Coverage](https://img.shields.io/codecov/c/github/Tyrrrz/DiscordChatExporter/master)](https://codecov.io/gh/Tyrrrz/DiscordChatExporter)
[![Release](https://img.shields.io/github/release/Tyrrrz/DiscordChatExporter.svg)](https://github.com/Tyrrrz/DiscordChatExporter/releases)
[![Downloads](https://img.shields.io/github/downloads/Tyrrrz/DiscordChatExporter/total.svg)](https://github.com/Tyrrrz/DiscordChatExporter/releases)
[![Pulls](https://img.shields.io/docker/pulls/tyrrrz/discordchatexporter)](https://hub.docker.com/r/tyrrrz/discordchatexporter)
[![Discord](https://img.shields.io/discord/869237470565392384?label=discord)](https://discord.gg/2SUWKFnHSm)

<table>
    <tr>
        <td width="99999" align="center">该项目的开发完全由社区资助。<b><a href="https://tyrrrz.me/donate">请考虑捐赠以支持他们！</a></b></td>
    </tr>
</table>

<p align="center">
    <img src="favicon.png" alt="Icon" />
</p>

**DiscordChatExporter** 是一个可用于将任何 [Discord](https://discord.com) 频道中的消息历史记录导出到文件的应用程序。
它适用于私聊信息、群组信息和服务器频道，并支持 Discord 的 Markdown 方言以及大多数其他富媒体功能。

> ❔ 如果您有任何疑问或问题，**请参阅 [文档](.docs)**。

> 💬 如果您想聊天，**请加入 [Discord 服务器](https://discord.gg/2SUWKFnHSm)**。

## 下载

> **注意**:
> 本 fork 致力于提供 DiscordChatExporter 的核心导出功能。
> 如果您通过以下链接访问原项目的发布页面，请注意其展示的信息和文档可能包含此 fork 未采纳的额外部分。
> 请注意，AUR 和 Nix 软件包通常基于原项目构建，其相关页面也可能包含额外的、此 fork 未采纳的内容。

- **图形用户界面** (桌面应用):
  - 🟢 **[Stable release](https://github.com/Tyrrrz/DiscordChatExporter/releases/latest)**: 查找 `DiscordChatExporter.*.zip`
  - 🟠 [CI build](https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml): 查找 `DiscordChatExporter.*.zip`
- **命令行界面** (终端应用):
  - 🟢 **[Stable release](https://github.com/Tyrrrz/DiscordChatExporter/releases/latest)**: 查找 `DiscordChatExporter.Cli.*.zip`
  - 🟠 [CI build](https://github.com/Tyrrrz/DiscordChatExporter/actions/workflows/main.yml): 查找 `DiscordChatExporter.Cli.*.zip`
  - 🐋 [Docker](https://hub.docker.com/r/tyrrrz/discordchatexporter): `docker pull tyrrrz/discordchatexporter`
  - 📦 [AUR](https://aur.archlinux.org/packages/discord-chat-exporter-cli): `discord-chat-exporter-cli`
  - 📦 [Nix](https://search.nixos.org/packages?query=discordchatexporter-cli): `discordchatexporter-cli`

> **重要提示**:
> 要在 MacOS 上启动 GUI 版本的应用程序，您需要首先将下载的文件从隔离区移除。
> 您可以通过在终端中运行以下命令来执行此操作：`xattr -rd com.apple.quarantine DiscordChatExporter.app`.

> **注意**:
> 如果您不确定哪个构建版本适合您的系统，请查阅 [此页面](https://useragent.cc) 以确定您的操作系统和 CPU 架构。

> **注意**:
> 上面链接的 AUR 和 Nix 软件包由社区维护。
> 如果您对它们有任何疑问，请联系相应的维护者。

## 功能特性

- 跨平台的图形用户界面和命令行界面
- 通过用户或机器人令牌进行身份验证
- 多种输出格式：HTML (深色/浅色模式)、TXT、CSV、JSON
- 支持 Markdown、附件、嵌入内容、表情符号和其他富媒体功能
- 文件分区、日期范围、消息过滤和其他导出选项
- 可离线查看的自包含导出文件

## 截图

![频道列表](.assets/list.png)
![渲染输出](.assets/output.png)

## 另请参阅

- [**Chat Analytics**](https://github.com/mlomb/chat-analytics) — 用于分析 Discord 用户聊天模式的解决方案，使用 **DiscordChatExporter** 生成的导出文件。
- [**DiscordChatExporter-frontend**](https://github.com/slatinsky/DiscordChatExporter-frontend) — **DiscordChatExporter** 生成的导出文件的便捷查看器。


## 关于此 Fork (About this Fork)

此版本是 [Tyrrrz/DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter) 的一个 fork，进行了一些内容调整，以使其更侧重于应用程序的核心功能。
此 fork 保留了原项目的捐款和社区链接，以支持项目的技术发展。
