# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — Based on Debian Testing

A Linux distribution for everyone. Play games and learn ethical hacking.

**🌐 Language:**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 The sections below are collapsed. Click **"▶ Click to expand"** on each one to keep reading.

<details>
<summary><b>📦 HackerOS Editions (click to expand)</b></summary>

## Official
The standard edition of HackerOS. Intended for casual users and gamers.

## Cybersecurity
An edition aimed at cybersecurity work in general. It features a dedicated kernel (the HackerOS Kernel) optimized for cybersecurity tasks, a set of proprietary cybersecurity tools, and, in the future, a proprietary GhostFS file system. Based on Debian Stable.

## Cybersecurity Default
A HackerOS edition tailored for cybersecurity and designed exclusively for Red Teams. In addition to everything found in the standard Cybersecurity edition, "Cybersecurity Default" includes the Xen Hypervisor and a dedicated Red Team session known as "Penetration Mode."

## NVIDIA
A copy of the Official edition with NVIDIA drivers pre-installed.

### Xfce
The same as the Official edition, but with Xfce instead of KDE.

### GNOME
The same as the Official edition, but with GNOME instead of KDE.

### Hydra
Has the look of Garuda Linux (partially) and is otherwise identical to the Official edition.

### Blue
A HackerOS edition featuring a custom graphical environment.

## LTS
The same as the Official edition, but built on Debian Stable instead of Debian Testing.

## Gaming
A SteamOS-inspired edition featuring the XanMod LTS kernel and a SteamOS-like Game Mode.

## Atomic
The immutable edition of HackerOS. It uses atomic package transactions, where each operation creates a new generation (gen-N) stored in a content-addressed store. Changes can be activated immediately (user mode) or after a reboot (system mode), with rollback support via GRUB. An integrity guardian keeps the package store read-only and cryptographically verified.

### How often is HackerOS released?
HackerOS follows a two-month release cycle. The Xfce, GNOME, Blue, and Hydra editions are released as x.0 and x.5 versions. The LTS edition ships only with x.0 releases, the Gaming edition ships with x.3 and x.7 releases, and the Atomic edition ships with x.1 and x.9 releases.

</details>

<details>
<summary><b>❓ Frequently Asked Questions (click to expand)</b></summary>

**Where can I find the H# website?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**Where can I find the bytes.io website?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**Where can I find the Hacker Lang website?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**Where can I find bit.io?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ HackerOS CLI Tools (click to expand)</b></summary>

### hacker
The heart of HackerOS. Installs additional software and updates the entire system quickly (Flatpak, snapshots, firmware, and APT).

### hl
Interpreter for Hacker Lang.

### bit
Package manager for Hacker Lang.

### h#
LLVM-based compiler and interpreter for the H# programming language.

### bytes
Package manager for H#.

### virus
Package manager for HackerScript.

### hackerc
Transpiler/compiler for HackerScript.

### hpm
Community repository tool inspired by `yay`.

### HackerOS Steam
Steam running inside an Arch container.

### getit
An alternative to `wget`/`git`. Can also be used to download individual directories from GitHub or GitLab.

### chker (choker)
CLI tool for switching the system kernel — removes the current Debian kernel and installs a custom one (XanMod or Liquorix).

### hup
Automatic update system.

### hedit
Nano-inspired text editor.

### ngt
A terminal-based (TUI) file manager with a built-in text editor and command console.

### isolator
Will be available on the Atomic edition in the future. Lets you run tools from multiple containers as regular applications, with its own dedicated package list/repository.

### hammer
Atomic CLI tool for the HackerOS Atomic edition.

### bph
Penetration testing tool, well suited for beginners.

### HexAI
AI assistant for HackerOS.

### HackerOS Builder
Special live-build overlay for easier image building.

### GameFrame
A Gamescope-inspired compositor for older graphics cards.

</details>

<details>
<summary><b>📱 HackerOS Apps (click to expand)</b></summary>

### Hacker Term
Terminal application for HackerOS.

### HackerOS App
Companion application for phones.

### HackerOS Game Mode
Activated with Ctrl+G. An application inspired by Asus Armoury Crate.

### HackerOS Welcome
The welcome application shown on first boot.

### Hacker Launcher
Designed primarily to run `.exe` applications.

### HackerOS Store
Install game launchers, penetration testing tools, drivers, and applications.

</details>

<details>
<summary><b>🖥️ HackerOS Sessions (click to expand)</b></summary>

### Hacker Mode
A session that uses its own compositor. Install it with `hacker unpack hacker-mode`.

### HackerOS TV
A media-watching session. Install it with `hacker unpack hackeros-tv`.

### gamescope-session-steam
A dedicated Steam session (similar to Bazzite or ChimeraOS) that uses the HackerOS-Steam container for Steam and Gamescope. Used in the Gaming edition.

### Cybersecurity Edition
The graphical environment and a dedicated session for the Cybersecurity edition.

</details>

<details>
<summary><b>⚙️ Configuration Formats (click to expand)</b></summary>

### .hk
Used as a library format for Rust, H#, and Hacker Lang.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
Documentation for both formats is available here: [.hk and .hacker docs](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

Documentation for all HackerOS tools can be found here: [HackerOS Tools Docs](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Screenshots (click to expand)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
