<p align="center">
  <img src="assets/subisland-github-hero.png" alt="SubIsland for macOS and Windows" width="100%">
</p>

<h1 align="center">SubIsland</h1>

<p align="center">
  把电脑负载与 Sub2API 状态放在屏幕顶端。<br>
  System load and Sub2API status, always visible at the top.
</p>

<p align="center">
  <img alt="macOS 13+" src="https://img.shields.io/badge/macOS-13%2B-111111?style=flat-square&logo=apple">
  <img alt="Windows 10+" src="https://img.shields.io/badge/Windows-10%2B-0078d4?style=flat-square&logo=windows">
  <img alt="Universal 2" src="https://img.shields.io/badge/macOS-Universal%202-2997ff?style=flat-square">
  <img alt="Windows x64" src="https://img.shields.io/badge/Windows-x64-64d2ff?style=flat-square">
  <img alt="Binary only" src="https://img.shields.io/badge/distribution-binary%20only-30d158?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/DAWU210/SubIsland/releases/latest"><strong>下载最新版本 · Download Latest Release</strong></a>
  &nbsp;·&nbsp;
  <a href="#中文">中文</a>
  &nbsp;·&nbsp;
  <a href="#english">English</a>
</p>

---

## 中文

SubIsland 是一款适用于 macOS 和 Windows 的轻量顶部状态岛，用于集中查看电脑负载与 Sub2API 账号状态。Sub2API 可以运行在本机、局域网或远程服务器上；客户端只需能够访问服务器地址。

- 收起时显示账号可用数、CPU、内存、5 小时和 7 天用量
- 支持“简略 / 详细”两种显示模式
- 没有启用账号时自动收缩为电脑状态模式
- 展开后仅显示启用账号，并按正在并发、可用度和用量状态排序
- 展示当前并发、套餐用量、冷却和重置时间
- 只读连接，不修改 Sub2API 账号设置
- macOS 使用系统钥匙串，Windows 使用系统凭据管理器保存刷新令牌
- 全屏应用运行时自动隐藏

> 远程 Sub2API 必须使用 HTTPS。管理员凭据仍具有完整后台权限，请勿分享给不可信的使用者。

## English

SubIsland is a lightweight top-center status island for macOS and Windows. It monitors system load and Sub2API account availability from a local, LAN, or remote deployment.

- Collapsed account availability, CPU, memory, 5-hour, and 7-day summaries
- Concise and detailed display modes
- Automatic computer-only mode when no Sub2API accounts are enabled
- Enabled accounts only, ordered by active concurrency and availability
- Expanded concurrency, quota usage, cooldown, and reset details
- Read-only Sub2API access that never changes account settings
- Refresh tokens stored in macOS Keychain or Windows Credential Manager
- Automatic hiding while another app is full screen

> Use HTTPS for every remote Sub2API deployment. Administrator credentials retain full dashboard privileges and should not be shared with untrusted users.

## 界面预览 · Preview

<p align="center">
  <img src="assets/subisland-social.png" alt="SubIsland cross-platform feature preview" width="520">
</p>

## 下载 · Download

| 平台 · Platform | 文件 · File | 用途 · Use |
| --- | --- | --- |
| macOS | [DMG](https://github.com/DAWU210/SubIsland/releases/download/v1.0.0/SubIsland-1.0.0-macOS-Universal.dmg) | 推荐安装方式 · Recommended installer |
| macOS | [ZIP](https://github.com/DAWU210/SubIsland/releases/download/v1.0.0/SubIsland-1.0.0-macOS-Universal.zip) | 便携应用压缩包 · Portable app archive |
| Windows x64 | [EXE](https://github.com/DAWU210/SubIsland/releases/download/v1.0.0/SubIsland-1.0.0-Windows-x64.exe) | 自包含便携程序 · Self-contained portable app |
| Windows x64 | [ZIP](https://github.com/DAWU210/SubIsland/releases/download/v1.0.0/SubIsland-1.0.0-Windows-x64.zip) | EXE 压缩包 · Portable archive |
| 校验 · Checksums | [macOS](https://github.com/DAWU210/SubIsland/releases/download/v1.0.0/SHA256SUMS.txt) · [Windows](https://github.com/DAWU210/SubIsland/releases/download/v1.0.0/SHA256SUMS-Windows.txt) | SHA-256 下载完整性校验 |

**系统要求 · Requirements**

- macOS 13 or later: Universal 2 for Intel and Apple silicon
- Windows 10 version 2004 or later / Windows 11: x64
- Remote Sub2API access: HTTPS strongly required

## 首次打开 · First Launch

**macOS**

> 当前 macOS 安装包为 ad-hoc 签名。首次运行时，请在 Finder 中右键点击 `SubIsland.app`，选择“打开”。
>
> The macOS build is ad-hoc signed. On first launch, right-click `SubIsland.app` in Finder and choose **Open**.

**Windows**

> 当前 Windows 版本未进行商业代码签名。若 SmartScreen 提示，请确认下载来自本仓库，然后选择“更多信息”→“仍要运行”。
>
> The Windows build is currently unsigned. If SmartScreen appears, verify that the download came from this repository, then choose **More info** → **Run anyway**.

## 隐私 · Privacy

本仓库仅分发编译后的安装包，不公开项目源码。发布包不包含账号、密码、令牌、钥匙串、Windows 凭据、偏好设置、日志或本机路径。运行时只在当前电脑保存服务器地址和显示设置；刷新令牌由系统凭据库保护。

This repository distributes compiled binaries only. Source code is not published. Release packages contain no accounts, passwords, tokens, credential-vault data, preferences, logs, or local machine paths. At runtime, only the server address and display preferences are stored locally; refresh tokens are protected by the operating system credential vault.

<sub>Binary distribution only · All rights reserved</sub>
