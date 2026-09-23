# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — Basierend auf Debian Testing

Eine Linux-Distribution für jeden. Spiele und lerne ethisches Hacken.

**🌐 Sprache:**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 Die folgenden Abschnitte sind eingeklappt. Klicke bei jedem auf **„▶ Aufklappen"**, um weiterzulesen.

<details>
<summary><b>📦 HackerOS-Editionen (zum Aufklappen klicken)</b></summary>

## Official
Die Standardedition von HackerOS. Gedacht für Gelegenheitsnutzer und Gamer.

## Cybersecurity
Eine Edition, die sich allgemein auf Cybersicherheit konzentriert. Sie bietet einen dedizierten Kernel (den HackerOS Kernel), der für Sicherheitsaufgaben optimiert ist, eine Reihe proprietärer Cybersecurity-Tools und in Zukunft ein proprietäres GhostFS-Dateisystem. Basierend auf Debian Stable.

## Cybersecurity Default
Eine HackerOS-Edition, die ausschließlich für Red Teams entwickelt wurde. Zusätzlich zu allem, was die Standard-Cybersecurity-Edition bietet, enthält „Cybersecurity Default" den Xen Hypervisor sowie eine dedizierte Red-Team-Sitzung namens „Penetration Mode".

## NVIDIA
Eine Kopie der Official-Edition mit vorinstallierten NVIDIA-Treibern.

### Xfce
Identisch mit der Official-Edition, jedoch mit Xfce statt KDE.

### GNOME
Identisch mit der Official-Edition, jedoch mit GNOME statt KDE.

### Hydra
Hat (teilweise) das Erscheinungsbild von Garuda Linux und ist ansonsten mit der Official-Edition identisch.

### Blue
Eine HackerOS-Edition mit einer eigenen, angepassten grafischen Umgebung.

## LTS
Identisch mit der Official-Edition, basiert jedoch auf Debian Stable statt Debian Testing.

## Gaming
Eine von SteamOS inspirierte Edition mit dem XanMod-LTS-Kernel und einem SteamOS-ähnlichen Spielmodus.

## Atomic
Die unveränderliche (immutable) Edition von HackerOS. Sie verwendet atomare Paket-Transaktionen, bei denen jede Operation eine neue Generation (gen-N) erzeugt, die in einem inhaltsadressierten Speicher abgelegt wird. Änderungen können sofort (Benutzermodus) oder nach einem Neustart (Systemmodus) aktiviert werden, mit Rollback-Unterstützung über GRUB. Ein Integritätswächter sorgt dafür, dass der Paketspeicher schreibgeschützt und kryptografisch verifiziert bleibt.

### Wie oft wird HackerOS veröffentlicht?
HackerOS folgt einem zweimonatigen Release-Zyklus. Die Editionen Xfce, GNOME, Blue und Hydra erscheinen als x.0- und x.5-Versionen. Die LTS-Edition erscheint ausschließlich mit x.0-Releases, die Gaming-Edition mit x.3- und x.7-Releases, und die Atomic-Edition mit x.1- und x.9-Releases.

</details>

<details>
<summary><b>❓ Häufig gestellte Fragen (zum Aufklappen klicken)</b></summary>

**Wo finde ich die H#-Website?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**Wo finde ich die bytes.io-Website?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**Wo finde ich die Hacker-Lang-Website?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**Wo finde ich bit.io?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ HackerOS-CLI-Tools (zum Aufklappen klicken)</b></summary>

### hacker
Das Herzstück von HackerOS. Installiert zusätzliche Software und aktualisiert das gesamte System schnell (Flatpak, Snapshots, Firmware und APT).

### hl
Interpreter für Hacker Lang.

### bit
Paketmanager für Hacker Lang.

### h#
LLVM-basierter Compiler und Interpreter für die Programmiersprache H#.

### bytes
Paketmanager für H#.

### virus
Paketmanager für HackerScript.

### hackerc
Transpiler/Compiler für HackerScript.

### hpm
Community-Repository-Tool, inspiriert von `yay`.

### HackerOS Steam
Steam, ausgeführt in einem Arch-Container.

### getit
Eine Alternative zu `wget`/`git`. Kann auch verwendet werden, um einzelne Verzeichnisse von GitHub oder GitLab herunterzuladen.

### chker (choker)
CLI-Tool zum Wechseln des Systemkernels — entfernt den aktuellen Debian-Kernel und installiert einen benutzerdefinierten (XanMod oder Liquorix).

### hup
Automatisches Update-System.

### hedit
Von Nano inspirierter Texteditor.

### ngt
Ein terminalbasierter (TUI) Dateimanager mit integriertem Texteditor und Befehlskonsole.

### isolator
Wird in Zukunft in der Atomic-Edition verfügbar sein. Ermöglicht das Ausführen von Tools aus mehreren Containern als reguläre Anwendungen, mit eigener dedizierter Paketliste/eigenem Repository.

### hammer
Atomares CLI-Tool für die HackerOS-Atomic-Edition.

### bph
Werkzeug für Penetrationstests, gut geeignet für Einsteiger.

### HexAI
KI-Assistent für HackerOS.

### HackerOS Builder
Spezielles Live-Build-Overlay zur einfacheren Erstellung von Images.

### GameFrame
Ein von Gamescope inspirierter Compositor für ältere Grafikkarten.

</details>

<details>
<summary><b>📱 HackerOS-Apps (zum Aufklappen klicken)</b></summary>

### Hacker Term
Terminal-Anwendung für HackerOS.

### HackerOS App
Begleit-App für Smartphones.

### HackerOS Game Mode
Aktiviert mit Strg+G. Eine von Asus Armoury Crate inspirierte Anwendung.

### HackerOS Welcome
Die beim ersten Start angezeigte Willkommens-App.

### Hacker Launcher
In erster Linie zum Ausführen von `.exe`-Anwendungen konzipiert.

### HackerOS Store
Installiere Game-Launcher, Penetrationstest-Tools, Treiber und Anwendungen.

</details>

<details>
<summary><b>🖥️ HackerOS-Sitzungen (zum Aufklappen klicken)</b></summary>

### Hacker Mode
Eine Sitzung mit eigenem Compositor. Installation mit `hacker unpack hacker-mode`.

### HackerOS TV
Eine Sitzung zum Medienschauen. Installation mit `hacker unpack hackeros-tv`.

### gamescope-session-steam
Eine dedizierte Steam-Sitzung (ähnlich wie Bazzite oder ChimeraOS), die den HackerOS-Steam-Container für Steam und Gamescope nutzt. Wird in der Gaming-Edition verwendet.

### Cybersecurity Edition
Die grafische Umgebung sowie eine dedizierte Sitzung für die Cybersecurity-Edition.

</details>

<details>
<summary><b>⚙️ Konfigurationsformate (zum Aufklappen klicken)</b></summary>

### .hk
Wird als Bibliotheksformat für Rust, H# und Hacker Lang verwendet.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
Dokumentation zu beiden Formaten ist hier verfügbar: [.hk- und .hacker-Dokumentation](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

Dokumentation zu allen HackerOS-Tools findest du hier: [HackerOS-Tools-Dokumentation](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Screenshots (zum Aufklappen klicken)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
