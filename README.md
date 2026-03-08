# WindTerm
一款更快更好的 SSH/Telnet/Serial/Shell/Sftp 客户端，专为 DevOps 打造。

_你好 WindTerm :rose:，你好世界！_

**我们才刚刚开始！如果你需要一款高性能文本编辑器，可以试试 [WindEdit](https://www.github.com/kingToolbox/WindEdit/)。**

# 许可证
**完全免费，可用于商业和非商业用途，无任何限制。**
**所有已发布的源代码（第三方目录除外）均基于 Apache-2.0 许可证条款提供。**

# 简介

查看 [介绍视频](https://kingtoolbox.github.io)

# 下载

**Linux 二进制文件**、**MacOS 二进制文件** 和 **Windows 二进制文件**：https://github.com/kingToolbox/WindTerm/releases

# 源代码

WindTerm 是一个**部分**开源项目，源代码将逐步开放。

开源代码包括但不限于可独立使用的类，如函数式、算法、GUI 组件等，以及功能库，如网络、协议等，以及所有根据许可证要求必须开源的类型。

# 问题与功能请求

欢迎提交任何问题和功能请求。

请点击 [issues](https://github.com/kingToolbox/WindTerm/issues) 提交问题或功能请求。

请点击 [讨论区](https://github.com/kingToolbox/WindTerm/discussions) 讨论有关 SSH、SFtp、Shell（Linux shell、Windows cmd 和 PowerShell）、Telnet、Serial 和 WindTerm 的任何话题。

# 截图

主窗口（zsh）：

![主窗口](https://github.com/kingToolbox/WindTerm/blob/master/images/screenshots/WindTerm.png)

分屏视图：

![分屏视图](https://github.com/kingToolbox/WindTerm/blob/master/images/screenshots/SplitView.png)

DigeWhite 主题：

![DigeWhite 主题](https://github.com/kingToolbox/WindTerm/blob/master/images/screenshots/WindTerm_DigeWhite_Theme.png)

# 功能特性

### SSH、Telnet、Tcp、Shell、Serial、Tmux
- 已实现 SSH v2、Telnet、Raw Tcp、Serial、Shell 协议。[介绍视频](https://kingtoolbox.github.io/2020/01/22/new-session/)
- 支持会话认证后 SSH 自动执行。
- 支持 SSH ControlMaster。
- 支持 SSH ProxyCommand 或 ProxyJump。[介绍视频](https://kingtoolbox.github.io/2021/03/11/proxycommand/)
- 支持 SSH 代理。[介绍视频](https://kingtoolbox.github.io/2020/08/22/ssh_agent/)
- 支持 SSH 代理转发。
- 支持使用密码、公钥、键盘交互、gssapi-with-mic 进行 SSH 自动登录。[介绍视频](https://kingtoolbox.github.io/2020/01/23/auto-login/)
- 支持 X11 转发。[介绍视频](https://kingtoolbox.github.io/2020/07/21/x11_forwarding/)
- 支持直接/本地端口转发、反向/远程端口转发和动态端口转发。[介绍视频](https://kingtoolbox.github.io/2020/07/21/port_forwarding/)
- 支持 XModem、YModem 和 ZModem。[介绍视频](https://kingtoolbox.github.io/tags/modem/)
- 集成 sftp、scp 客户端，支持下载、上传、删除、重命名、新建文件/目录等操作。[介绍视频](https://kingtoolbox.github.io/tags/transfer/)
- 集成本地文件管理器，支持移动、复制到、从...复制、删除、重命名、新建文件/目录等操作。
- 支持 Windows Cmd、PowerShell 以及以管理员身份运行 Cmd、PowerShell。
- 支持 Linux bash、zsh、PowerShell Core 等。
- 支持 MacOS bash、zsh、PowerShell Core 等。
- **支持 `tmux 集成`**。[介绍视频](https://kingtoolbox.github.io/2025/01/05/tmux-integration/)
### 图形界面
- **支持 Windows、MacOS 和 Linux。**
- **支持多语言用户界面。**
- 支持 Unicode 13。
- 会话对话框和会话树。[介绍视频](https://kingtoolbox.github.io/2020/01/22/manage-sessions/)
- **自动补全。**[介绍视频](https://kingtoolbox.github.io/tags/auto-completion/)
- **自由输入模式。**[介绍视频](https://kingtoolbox.github.io/2022/04/12/free_type_mode/)
- **专注模式。**[介绍视频](https://kingtoolbox.github.io/2021/06/28/ui_focus_mode/)
- **同步输入。**[介绍视频](https://kingtoolbox.github.io/2021/05/27/sync-input/)
- **增强的会话用户名和密码保护。**[介绍视频](https://kingtoolbox.github.io/2021/03/11/protection-username-password/)
- **命令面板。**[介绍视频](https://kingtoolbox.github.io/tags/command-palette/)
- **命令发送器。**[介绍视频](https://kingtoolbox.github.io/tags/sender/)
- **资源管理器面板。**[介绍视频](https://kingtoolbox.github.io/2021/05/27/explorer/)
- **Shell 面板。**
- **快捷栏。**[介绍视频](https://kingtoolbox.github.io/2020/08/22/quickbar/)
- **粘贴对话框。**[介绍视频](https://kingtoolbox.github.io/2020/08/22/paste_dialog/)
- **支持 vim 键绑定的本地和远程模式。（使用 Shift+Enter 键在远程和本地模式之间切换）**[介绍视频](https://kingtoolbox.github.io/2020/06/21/keyboard-modes/)
- 支持时间戳、折叠、大纲、分屏视图。
- **支持 Linux 和 PowerShell 中的 powerline，例如 Oh-My-Zsh、Oh-My-Posh。**[介绍图片](https://github.com/kingToolbox/WindTerm#screenshots)
- 支持类似 vscode 的配色方案。[介绍视频](https://kingtoolbox.github.io/2020/01/23/highlight/)
- 支持搜索和预览。[介绍视频](https://kingtoolbox.github.io/2020/01/22/search-and-mark/)
- 支持高亮显示匹配的开闭分隔符，如 ()、[]、{} 以及自定义分隔符。[介绍视频](https://kingtoolbox.github.io/2020/06/28/pair/)
- 支持更换界面主题。[介绍视频](https://kingtoolbox.github.io/2020/09/18/theme/)
- 支持设置标签页颜色。[介绍视频](https://kingtoolbox.github.io/2020/09/18/tabbar-change-tabcolor/)
- 支持在已打开的标签页中搜索。[介绍视频](https://kingtoolbox.github.io/2021/03/11/tabbar-search-tab/)
- 支持关闭右侧标签页。
- 支持设置窗口透明度。[介绍视频](https://kingtoolbox.github.io/2020/11/13/windows-opacity/)
- 支持选中即复制、右键粘贴或中键粘贴。
- 支持使用 Google、Bing、Github、Stackoverflow、Wikipedia 和 DuckDuckGo 在线搜索文本。[介绍视频](https://kingtoolbox.github.io/2020/11/13/search-online/)
- 支持输入时隐藏鼠标光标。
- **支持锁定屏幕。**[介绍视频](https://kingtoolbox.github.io/2021/04/23/lock-screen/)
### 终端
- 支持 vt100、vt220、vt340、vt420、vt520、xterm、xterm-256-colors。
- 支持 unicode、表情符号、真彩色、鼠标协议等。
- 支持自动换行模式。[介绍视频](https://kingtoolbox.github.io/2020/01/22/auto-wrap/)
- 协议和终端可自定义。
- 除 Tektronix 4014 外，所有 vttest 测试均已通过。
### 会话
- **支持 HTTP 和 SOCKS5 代理。**[介绍视频](https://kingtoolbox.github.io/2021/03/11/proxy-http-socks5/)
- **支持跳板机代理。**[介绍视频](https://kingtoolbox.github.io/2021/03/11/proxy-jump-server/)
- 支持手动和自动会话日志记录。[介绍视频](https://kingtoolbox.github.io/tags/logging/)
- 重命名和复制会话。[介绍视频](https://kingtoolbox.github.io/tags/tabbar/)
- 重启时恢复上次会话和布局。[介绍视频](https://kingtoolbox.github.io/2020/01/22/restore-sessions/)
- 支持启动时打开指定会话或一组会话。
### 性能
- 动态内存压缩，通常可减少 `20%` 到 `90%` 的工作内存负载。
- 高性能、低内存、低延迟。[介绍视频](https://kingtoolbox.github.io/2020/01/23/windterm-putty-performance/)

# Sftp 性能

用于生成以下基准测试数据的硬件为

    Windows 10 - 2.3 GHz Intel Core i5，8GB 内存。

**WindTerm 1.72、WindTerm 1.2、FileZilla 3.48.1、WinSCP 5.17.2（Build 10278）** 测试在 WSL（Ubuntu 18.04.2）上进行。

客户端版本：

| 应用程序 | 版本 | 发布日期 |
| --- | --- | --- |
| windterm | v1.72 | 2020-10-25 |
| windterm | v1.2 | 2020-06-15 |
| FileZilla | v3.48.1 | 2020-05-19 |
| WinScp | v5.17.2 (Build 10278) | 2020-03-09 |

**所有测试数据仅供参考。**

### 5GB 大文件（5,154,830 KB），由随机数据生成

| | 下载时间 | 下载速率 | 上传时间 | 上传速率 |
| --- | --- | --- | --- | --- |
| WindTerm 1.72（使用高速传输） | **23s** | **216.3 MB/s** | **20s** | **247.0 MB/s** |
| WindTerm 1.72 | **23s** | **214.7 MB/s** | **20s** | **244.0 MB/s** |
| WindTerm 1.2 | 37s | 139.3 MB/s | 43s | 119.9 MB/s |
| FileZilla | 32s | 161.1 MB/s | 30s | 171.8 MB/s |
| WinSCP | 81s | 63.7 MB/s | 91s | 56.7 MB/s |

### 4400 个文件，16 个文件夹（107,042 KB），解压自 [vim-7.4.1049.zip](https://github.com/vim/vim/archive/v7.4.1049.zip)

| | 下载时间 | 下载速率 | 上传时间 | 上传速率 |
| --- | --- | --- | --- | --- |
| WindTerm 1.7 | **26s** | **3.9 MB/s** | 13s | 8.1 MB/s |
| WindTerm 1.2 | 32s | 3.4 MB/s | **10s** | **10.7 MB/s** |
| FileZilla | 48s | 2.2 MB/s | 35s | 3.1 MB/s |
| WinSCP | 42s | 2.6 MB/s | 12s | 8.9 MB/s |

# 终端性能

用于生成以下基准测试数据的硬件为

    Windows 10 - 2.3 GHz Intel Core i5，8GB 内存。
    MacOS 10.13 - 2.3 GHz Intel Core i5，8GB 内存。

**WindTerm 1.72、rxvt、putty、xterm、Windows Terminal** 测试在 WSL（Ubuntu 18.04.2）上进行。

**Iterm2、kitty、Alacritty** 测试在 MacOS shell 上进行。

    对于 WindTerm：未使用配色方案。配色方案会导致约 2% 的性能损失和更多的内存使用。

    对于 Alacritty：最多仅支持 100,000 行回滚，因此每次测试使用 "history: 100000" 设置，未测量内存使用。

    对于 Windows Terminal：最多仅支持 65,535 行回滚，因此每次测试使用 "historySize: 65535" 设置，未测量内存使用。

终端版本：

| 应用程序 | 版本 | 发布日期 |
| --- | --- | --- |
| windterm | v1.72 | 2020-10-25 |
| rxvt-unicode | v9.2.2 | 2016-05-14 |
| putty | v0.71 | 2019-03-16 |
| xterm | v3.30 | 2017-06-20 |
| iterm2 | v3.3.6 | 2019-10-09 |
| alacritty | v0.5.0 | 2020-07-21 |
| kitty | v0.14.6 | 2019-09-25 |
| Windows Terminal | v1.3.2651.0 | 2020-09-22 |

**所有测试数据仅供参考。**

## 测试命令："cat ./benchmark_randomdata"

benchmark_randomdata 包含 97.6MB 随机文本（102,401,504 字节，1,329,878 行，由 [random_test.sh](https://github.com/kingToolbox/WindTerm/blob/master/benchmark/urandom_test.sh) 生成并测试）

所有情况下，先运行三次以预热系统缓存。报告的数字为五次运行的中位数。

1. Telnet：

| | 回滚行数 | 数据速率（MB/秒） | 内存使用（MB） |
| --- | --- | --- | --- |
| WindTerm | 无限制 | **52.1** | **106.6** |
| rxvt | 1,350,000 | 37.8 | 842.2 |
| Putty | 1,350,000 | 4.9 | 733.4 |
| xterm | 1,350,000 | 2.2 | 3328.4 |
| Windows Terminal + telnet.exe | 65,535 | 0.1 | 未测量，使用 65,535 回滚行设置 |

2. SSH：

| | 回滚行数 | 数据速率（MB/秒） | 内存使用（MB） |
| --- | --- | --- | --- |
| WindTerm | 无限制 | **41.8** | **108.5** |
| rxvt | 1,350,000 | 40.2 | 842.2 |
| Putty | 1,350,000 | 4.8 | 734.9 |
| xterm | 1,350,000 | 2.3 | 3328.4 |
| Windows Terminal + ssh.exe | 65,535 | 2.1 | 未测量，使用 65,535 回滚行设置 |

3. Shell：

| | 回滚行数 | 数据速率（MB/秒） | 内存使用（MB） |
| --- | --- | --- | --- |
| iterm2 | 无限制 | -（耗时过长） | 超过 1300 |
| kitty | 无限制 | 17.2 | 2655 |
| Alacritty | 100,000 | 41.3 | - |

## 测试命令："time seq 1 n"（n = [1000000, 2000000, 5000000, 10000000]，回滚行数：无限制）

### n = 1,000,000

| | 时间（秒） | 内存使用（MB） |
| --- | --- | --- |
| WindTerm | 1.236 | **16.1** |
| rxvt | 5.082 | 633.3 |
| putty | 4.161 | 551.1 |
| xterm | 40.421 | 2500.7 |
| iterm2 | 2.116 | 146.3 |
| Kitty | 2.535 | 2376.5 |
| Alacritty | **1.162** | 未测量，使用 100,000 回滚行设置 |
| Windows Terminal + ssh.exe | 23.246 | 未测量，使用 65,535 回滚行设置 |

### n = 2,000,000

| | 时间（秒） | 内存使用（MB） |
| --- | --- | --- |
| WindTerm | **2.287** | **24.1** |
| rxvt | 10.896 | 1266.6 |
| putty | 16.045 | 1102.6 |
| xterm | 68.154 | 5005.5 |
| iterm2 | 4.181 | 383.2 |
| Kitty | 5.620 | 4749.9 |
| Alacritty | 2.322 | 未测量，使用 100,000 回滚行设置 |
| Windows Terminal + ssh.exe | 50.381 | 未测量，使用 65,535 回滚行设置 |

### n = 5,000,000

| | 时间（秒） | 内存使用（MB） |
| --- | --- | --- |
| WindTerm | **5.520** | **68.2** |
| rxvt | 27.533 | 3166.2 |
| putty | 45.911 | 2757.1 |
| xterm | - | 内存不足 |
| iterm2 | 10.805 | 1048.3 |
| Kitty | - | 内存不足 |
| Alacritty | 5.799 | 未测量，使用 100,000 回滚行设置 |
| Windows Terminal + ssh.exe | 130.371 | 未测量，使用 65,535 回滚行设置 |

### n = 10,000,000

| | 时间（秒） | 内存使用（MB） |
| --- | --- | --- |
| WindTerm | **10.674** | **133.3** |
| rxvt | - | 内存不足 |
| putty | - | 内存不足 |
| xterm | - | 内存不足 |
| iterm2 | 20.468 | 2231.3 |
| Kitty | - | 内存不足 |
| Alacritty | 11.598 | 未测量，使用 100,000 回滚行设置 |
| Windows Terminal + ssh.exe | 264.739 | 未测量，使用 65,535 回滚行设置 |

### n = 10,000,000 回滚行数 = 30 行

| | 时间（秒） | 内存使用（MB） |
| --- | --- | --- |
| WindTerm | 10.167 | 0.7 |
| rxvt | **9.687** | **0.1** |
| putty | 95.382 | 0.4 |
| xterm | 286.510 | **0.1** |
| iterm2 | 25.448 | 7.4 |
| Kitty | 16.104 | 0.5 |
| Alacritty | 11.798 | 未测量，使用零回滚行设置 |
| Windows Terminal + ssh.exe | 261.096 | 未测量，使用零回滚行设置 |

# Linux 终端性能

用于生成以下基准测试数据的硬件为

    Debian 10 虚拟机 - 4 核 CPU，4GB 内存。

    对于 WindTerm：未使用配色方案。配色方案会导致约 2% 的性能损失和更多的内存使用。

    对于其他终端：未测量内存使用，因为大多数终端将历史记录写入磁盘或仅支持有限的内存行数。

终端版本：

| 应用程序 | 版本 | 发布日期 |
| --- | --- | --- |
| Windterm | v1.9 | 2020-12-22 |
| Gnome | v3.30.2 | 2018-10-22 |
| Mate Terminal | v1.20.2 | 2019-02-11 |
| Konsole | v18.04.0 | 2019-04-12 |
| Xfce4 Terminal | v0.8.7.4 | 2018-5-15 |
| QTerminal | v0.14.1 | 2019-01-26 |

**所有测试数据仅供参考。**

## 测试命令："cat ./benchmark_randomdata"

benchmark_randomdata 包含 97.6MB 随机文本（102,401,504 字节，1,329,878 行，由 [random_test.sh](https://github.com/kingToolbox/WindTerm/blob/master/benchmark/urandom_test.sh) 生成并测试）

所有情况下，先运行三次以预热系统缓存。报告的数字为五次运行的中位数。

| | 耗时 |
| --- | --- |
| WindTerm | **1.976s** |
| Gnome Terminal  | 9.781s |
| Mate Terminal  | 9.841s |
| Konsole | 25.050s |
| xfce4 Terminal | 10.520s |
| QTerminal | 20.763s |

## 测试命令："time seq 1 n"（n = [1000000, 2000000, 5000000, 10000000]，回滚行数：无限制）

| n | 1,000,000 | 2,000,000 | 5,000,000 | 10,000,000 | 10,000,000<br>（回滚行数：100） |
| --- | --- | --- | --- | --- | --- |
| WindTerm | 0.846s (18.6MB) | **1.574s** (26.6MB) | **4.046s** (56.4MB) | **8.232s** (102.2MB) | **7.748s** (3.4MB) |
| Gnome Terminal  | 0.920s | 2.152s | 5.271s | 11.111s | 13.109s |
| Mate Terminal  | **0.822s** | 1.698s | 5.943s | 10.920s | 12.290s |
| Konsole | 1.612s | 3.199s | 8.157s | 16.029s | 15.650s |
| xfce4 Terminal | 0.870s | 2.160s | 5.866s | 12.089s | 13.304s |
| QTerminal | 9.272s | 18.391s | 45.999s | 104.277s | 17.208s |

# 延迟

考虑到网络对延迟的影响，以下数据来自 [WindEdit](https://github.com/kingToolbox/digedit)。
DIGEdit 是 WindTerm 的文本组件。

|   | 最小值 | 最大值 | 平均值 | 标准差 |
| --- | --- | --- | --- | --- |
|WindEdit| 1.9 | 7.6 | 2.9 | 0.8 |
|Windows 记事本 | 0.9 | 16.5 | 7.8 | 1.8 |
|GVim | 0.9 | 10.4 | 2.8 | 1.2 |

# 快捷键

[快捷键列表](https://kingtoolbox.github.io/tags/keyboard/)

# 路线图

**发布周期：**

  2-3 个月。

**预发布周期：**

  4~6 周

# v2.7 路线图（2025 年 2 月，仅供参考）
- **尽可能多地解决问题**
- SSH 代理转发
- Tmux 集成
- 命令片段 [描述](https://github.com/kingToolbox/WindTerm/issues/239#issuecomment-951934488)（推迟到后续版本）
- SSH GSSAPI 认证（推迟到后续版本）
- 会话内搜索（推迟到后续版本）

下载：[WindTerm 2.7.0 预发布版 3](https://github.com/kingToolbox/WindTerm/releases/tag/2.7-prerelease-3)（2025-2-10）

**2.x 版本路线图：**
- 外部工具
- 协议：
  - Mosh
  - Rlogin
- 会话：
  - 自动补全
  - 聊天模式
  - 日志查看器
- 文件传输：
  - ftp、ftps
- 脚本、宏和插件系统
- 更多功能...

**发布计划：**
版本 | 级别 | 目标 | 状态 | 时间线
------------ | ------------- | -------------- | ---------- | -----------
v0.x | 基础 | 基础框架和基本功能，但完成了一个高性能文本编辑器（[WindEdit](https://github.com/kingToolbox/WindEdit)）作为基础，并能够正常使用。 | 已完成 | 很久以前 ~ 2020 年春
v1.x | 手动 | 完善功能，大多数开发者可在日常工作中使用 | 已完成 | 2020 年春 ~ 2020 年冬
**v2.x** | **半自动** | **通过触发器、宏、事件、通知等，辅助开发者完成部分操作。** | **开发中** | **2021 年春 ~ 2022 年夏**
v3.x | 全自动 | 通过插件、脚本、机器学习等，实现自动化运维，达到无人值守 | 规划中 | 2022 年夏 ~ 2023 年冬

# 致谢
|            | 贡献  |
| ---------- | ------------- |
| [EvoWebFrance](https://github.com/EvoWebFrance) | 法语翻译 |
| [kvnklk](https://github.com/kvnklk) | 德语翻译 |
| [Lemonawa](https://github.com/Lemonawa) | 简体中文翻译 |
| [LuxNegra](https://github.com/LuxNegra) | 法语翻译 |
| [MosamXu](https://github.com/MosamXu) | 简体中文翻译 |
