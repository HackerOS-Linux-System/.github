# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — 基于 Debian Testing

一款适合所有人的 Linux 发行版。畅玩游戏，学习道德黑客技术。

**🌐 语言：**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 以下各部分默认收起。点击每个部分的 **「▶ 点击展开」** 继续阅读。

<details>
<summary><b>📦 HackerOS 版本（点击展开）</b></summary>

## Official（官方版）
HackerOS 的标准版本，面向普通用户和游戏玩家。

## Cybersecurity（网络安全版）
面向网络安全领域的通用版本。配备专用内核（HackerOS Kernel），针对安全任务进行了优化，并集成了一系列专有的网络安全工具；未来还将加入专有的 GhostFS 文件系统。基于 Debian Stable 构建。

## Cybersecurity Default（网络安全默认版）
专为红队（Red Team）设计的 HackerOS 版本。除了标准网络安全版的全部功能外，「Cybersecurity Default」还内置了 Xen 虚拟机监控程序，以及名为「Penetration Mode」的专用红队会话。

## NVIDIA
官方版的副本，预装了 NVIDIA 驱动。

### Xfce
与官方版相同，但使用 Xfce 而非 KDE。

### GNOME
与官方版相同，但使用 GNOME 而非 KDE。

### Hydra
外观部分借鉴自 Garuda Linux，其余部分与官方版相同。

### Blue
配备自定义图形环境的 HackerOS 版本。

## LTS
与官方版相同，但基于 Debian Stable 而非 Debian Testing 构建。

## Gaming（游戏版）
灵感来自 SteamOS 的版本，搭载 XanMod LTS 内核，并提供类似 SteamOS 的游戏模式。

## Atomic（原子版）
HackerOS 的不可变版本。采用原子化软件包事务机制，每次操作都会生成一个新的世代（gen-N），存储在按内容寻址的存储库中。更改可以立即生效（用户模式）或在重启后生效（系统模式），并通过 GRUB 支持回滚。完整性守护程序确保软件包存储库始终只读且经过加密验证。

### HackerOS 多久发布一次新版本？
HackerOS 遵循两个月一次的发布周期。Xfce、GNOME、Blue 和 Hydra 版本以 x.0 和 x.5 版本号发布；LTS 版本仅随 x.0 版本发布；Gaming 版本随 x.3 和 x.7 版本发布；Atomic 版本随 x.1 和 x.9 版本发布。

</details>

<details>
<summary><b>❓ 常见问题（点击展开）</b></summary>

**在哪里可以找到 H# 的网站？**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**在哪里可以找到 bytes.io 的网站？**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**在哪里可以找到 Hacker Lang 的网站？**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**在哪里可以找到 bit.io？**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ HackerOS 命令行工具（点击展开）</b></summary>

### hacker
HackerOS 的核心工具，用于安装额外软件并快速更新整个系统（涵盖 Flatpak、快照、固件和 APT）。

### hl
Hacker Lang 语言的解释器。

### bit
Hacker Lang 的包管理器。

### h#
基于 LLVM 的 H# 编程语言编译器与解释器。

### bytes
H# 的包管理器。

### virus
HackerScript 的包管理器。

### hackerc
HackerScript 的转译器/编译器。

### hpm
受 `yay` 启发的社区仓库工具。

### HackerOS Steam
在 Arch 容器中运行的 Steam。

### getit
`wget`/`git` 的替代工具，也可用于从 GitHub 或 GitLab 下载单个目录。

### chker（choker）
用于切换系统内核的命令行工具——移除当前的 Debian 内核并安装自定义内核（XanMod 或 Liquorix）。

### hup
自动更新系统。

### hedit
受 Nano 启发的文本编辑器。

### ngt
基于终端的（TUI）文件管理器，内置文本编辑器和命令控制台。

### isolator
未来将在 Atomic 版本中提供。可将来自多个容器的工具作为普通应用程序运行,并拥有自己专属的软件包列表/仓库。

### hammer
适用于 HackerOS Atomic 版本的原子化命令行工具。

### bph
渗透测试工具,非常适合初学者使用。

### HexAI
HackerOS 的 AI 助手。

### HackerOS Builder
特殊的实时构建覆盖层,便于镜像构建。

### GameFrame
受 Gamescope 启发的合成器,适用于较旧的显卡。

</details>

<details>
<summary><b>📱 HackerOS 应用程序（点击展开）</b></summary>

### Hacker Term
HackerOS 的终端应用程序。

### HackerOS App
面向手机的配套应用程序。

### HackerOS Game Mode
通过 Ctrl+G 激活,灵感来自 Asus Armoury Crate 的应用程序。

### HackerOS Welcome
首次启动时显示的欢迎应用程序。

### Hacker Launcher
主要用于运行 `.exe` 应用程序。

### HackerOS Store
安装游戏启动器、渗透测试工具、驱动程序和各类应用程序。

</details>

<details>
<summary><b>🖥️ HackerOS 会话（点击展开）</b></summary>

### Hacker Mode
使用自有合成器的会话。使用 `hacker unpack hacker-mode` 安装。

### HackerOS TV
用于观看多媒体内容的会话。使用 `hacker unpack hackeros-tv` 安装。

### gamescope-session-steam
专用的 Steam 会话(类似于 Bazzite 或 ChimeraOS),使用 HackerOS-Steam 容器运行 Steam 和 Gamescope,用于 Gaming 版本。

### Cybersecurity Edition
网络安全版本的图形环境及专用会话。

</details>

<details>
<summary><b>⚙️ 配置文件格式（点击展开）</b></summary>

### .hk
用作 Rust、H# 和 Hacker Lang 的库格式。

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
两种格式的文档可在此查看：[.hk 与 .hacker 文档](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

所有 HackerOS 工具的文档可在此查看：[HackerOS 工具文档](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ 截图（点击展开）</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
