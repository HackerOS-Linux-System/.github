# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — oparty na Debianie Testing

Dystrybucja Linuksa dla każdego. Graj i ucz się etycznego hakowania.

**🌐 Język:**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 Poniższe sekcje są zwinięte. Kliknij **„▶ Rozwiń"** przy każdej z nich, aby czytać dalej.

<details>
<summary><b>📦 Edycje HackerOS (kliknij, aby rozwinąć)</b></summary>

## Official
Standardowa edycja HackerOS. Przeznaczona dla zwykłych użytkowników i graczy.

## Cybersecurity
Edycja ukierunkowana ogólnie na cyberbezpieczeństwo. Zawiera dedykowane jądro (HackerOS Kernel) zoptymalizowane pod kątem zadań związanych z bezpieczeństwem, zestaw autorskich narzędzi cyberbezpieczeństwa oraz — w przyszłości — autorski system plików GhostFS. Oparta na Debianie Stable.

## Cybersecurity Default
Edycja HackerOS przeznaczona wyłącznie dla zespołów Red Team. Oprócz wszystkiego, co znajduje się w standardowej edycji Cybersecurity, „Cybersecurity Default" zawiera hipervizor Xen oraz dedykowaną sesję Red Team znaną jako „Penetration Mode".

## NVIDIA
Kopia edycji Official z fabrycznie zainstalowanymi sterownikami NVIDIA.

### Xfce
To samo co edycja Official, ale zamiast KDE zawiera Xfce.

### GNOME
To samo co edycja Official, ale zamiast KDE zawiera GNOME.

### Hydra
Posiada wygląd (częściowo) zbliżony do Garuda Linux, poza tym identyczna z edycją Official.

### Blue
Edycja HackerOS z własnym, niestandardowym środowiskiem graficznym.

## LTS
To samo co edycja Official, ale zbudowana na Debianie Stable zamiast Debianie Testing.

## Gaming
Edycja inspirowana SteamOS, zawierająca jądro XanMod LTS oraz tryb gry podobny do tego z SteamOS.

## Atomic
Niemutowalna (immutable) edycja HackerOS. Wykorzystuje atomowe transakcje pakietów, gdzie każda operacja tworzy nową generację (gen-N) przechowywaną w magazynie adresowanym treścią. Zmiany mogą być aktywowane natychmiast (tryb użytkownika) lub po restarcie (tryb systemowy), z możliwością cofnięcia (rollback) przez GRUB. Strażnik integralności dba o to, by magazyn pakietów pozostawał tylko do odczytu i był kryptograficznie zweryfikowany.

### Jak często wydawany jest HackerOS?
HackerOS wydawany jest w dwumiesięcznym cyklu. Edycje Xfce, GNOME, Blue i Hydra są wydawane jako wersje x.0 i x.5. Edycja LTS dostępna jest wyłącznie z wydaniami x.0, edycja Gaming z wydaniami x.3 i x.7, a edycja Atomic z wydaniami x.1 i x.9.

</details>

<details>
<summary><b>❓ Najczęściej zadawane pytania (kliknij, aby rozwinąć)</b></summary>

**Gdzie znajdę stronę H#?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**Gdzie znajdę stronę bytes.io?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**Gdzie znajdę stronę Hacker Lang?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**Gdzie znajdę bit.io?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ Narzędzia CLI HackerOS (kliknij, aby rozwinąć)</b></summary>

### hacker
Serce HackerOS. Instaluje dodatkowe oprogramowanie i szybko aktualizuje cały system (Flatpak, snapshoty, firmware oraz APT).

### hl
Interpreter języka Hacker Lang.

### bit
Menedżer pakietów dla Hacker Lang.

### h#
Kompilator i interpreter oparty na LLVM dla języka programowania H#.

### bytes
Menedżer pakietów dla H#.

### virus
Menedżer pakietów dla HackerScript.

### hackerc
Transpiler/kompilator dla HackerScript.

### hpm
Narzędzie repozytorium społecznościowego inspirowane `yay`.

### HackerOS Steam
Steam uruchamiany w kontenerze Arch.

### getit
Alternatywa dla `wget`/`git`. Można go również użyć do pobierania pojedynczych katalogów z GitHuba lub GitLaba.

### chker (choker)
Narzędzie CLI do zmiany jądra systemu — usuwa bieżące jądro Debiana i instaluje niestandardowe (XanMod lub Liquorix).

### hup
Automatyczny system aktualizacji.

### hedit
Edytor tekstu inspirowany Nano.

### ngt
Terminalowy (TUI) menedżer plików z wbudowanym edytorem tekstu i konsolą poleceń.

### isolator
W przyszłości dostępny w edycji Atomic. Pozwala uruchamiać narzędzia z wielu kontenerów jako zwykłe aplikacje, z własną, dedykowaną listą pakietów/repozytorium.

### hammer
Atomowe narzędzie CLI dla edycji HackerOS Atomic.

### bph
Narzędzie do testów penetracyjnych, dobrze dopasowane dla początkujących.

### HexAI
Asystent AI dla HackerOS.

### HackerOS Builder
Specjalna nakładka do budowania obrazów live, ułatwiająca ich tworzenie.

### GameFrame
Kompozytor inspirowany Gamescope, przeznaczony dla starszych kart graficznych.

</details>

<details>
<summary><b>📱 Aplikacje HackerOS (kliknij, aby rozwinąć)</b></summary>

### Hacker Term
Aplikacja terminala dla HackerOS.

### HackerOS App
Aplikacja towarzysząca na telefony.

### HackerOS Game Mode
Aktywowany kombinacją Ctrl+G. Aplikacja inspirowana Asus Armoury Crate.

### HackerOS Welcome
Aplikacja powitalna wyświetlana przy pierwszym uruchomieniu.

### Hacker Launcher
Zaprojektowany głównie do uruchamiania aplikacji `.exe`.

### HackerOS Store
Instaluj launchery gier, narzędzia do testów penetracyjnych, sterowniki i aplikacje.

</details>

<details>
<summary><b>🖥️ Sesje HackerOS (kliknij, aby rozwinąć)</b></summary>

### Hacker Mode
Sesja korzystająca z własnego kompozytora. Zainstaluj ją poleceniem `hacker unpack hacker-mode`.

### HackerOS TV
Sesja do oglądania multimediów. Zainstaluj ją poleceniem `hacker unpack hackeros-tv`.

### gamescope-session-steam
Dedykowana sesja Steam (podobna do Bazzite lub ChimeraOS), wykorzystująca kontener HackerOS-Steam dla Steama i Gamescope. Używana w edycji Gaming.

### Cybersecurity Edition
Środowisko graficzne oraz dedykowana sesja dla edycji Cybersecurity.

</details>

<details>
<summary><b>⚙️ Formaty konfiguracji (kliknij, aby rozwinąć)</b></summary>

### .hk
Używany jako format biblioteki dla Rusta, H# oraz Hacker Lang.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
Dokumentacja obu formatów dostępna jest tutaj: [dokumentacja .hk i .hacker](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

Dokumentację wszystkich narzędzi HackerOS znajdziesz tutaj: [Dokumentacja narzędzi HackerOS](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Zrzuty ekranu (kliknij, aby rozwinąć)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
