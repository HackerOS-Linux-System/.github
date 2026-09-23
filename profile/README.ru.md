# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — на основе Debian Testing

Дистрибутив Linux для всех. Играйте и изучайте этичный хакинг.

**🌐 Язык:**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 Разделы ниже свёрнуты. Нажмите **«▶ Развернуть»** у каждого, чтобы читать дальше.

<details>
<summary><b>📦 Издания HackerOS (нажмите, чтобы развернуть)</b></summary>

## Official
Стандартное издание HackerOS. Предназначено для обычных пользователей и геймеров.

## Cybersecurity
Издание, ориентированное в целом на кибербезопасность. Включает выделенное ядро (HackerOS Kernel), оптимизированное для задач безопасности, набор проприетарных инструментов кибербезопасности, а в будущем — проприетарную файловую систему GhostFS. Основано на Debian Stable.

## Cybersecurity Default
Издание HackerOS, разработанное исключительно для команд Red Team. Помимо всего, что есть в стандартном издании Cybersecurity, «Cybersecurity Default» включает гипервизор Xen и выделенную сессию Red Team под названием «Penetration Mode».

## NVIDIA
Копия издания Official с предустановленными драйверами NVIDIA.

### Xfce
То же, что и издание Official, но с Xfce вместо KDE.

### GNOME
То же, что и издание Official, но с GNOME вместо KDE.

### Hydra
Частично имеет внешний вид Garuda Linux, в остальном идентично изданию Official.

### Blue
Издание HackerOS с собственным, настраиваемым графическим окружением.

## LTS
То же, что и издание Official, но собрано на основе Debian Stable вместо Debian Testing.

## Gaming
Издание, вдохновлённое SteamOS, с ядром XanMod LTS и игровым режимом в стиле SteamOS.

## Atomic
Неизменяемое (immutable) издание HackerOS. Использует атомарные транзакции пакетов, где каждая операция создаёт новое поколение (gen-N), хранящееся в хранилище с адресацией по содержимому. Изменения могут применяться сразу (пользовательский режим) или после перезагрузки (системный режим), с поддержкой отката через GRUB. Страж целостности следит за тем, чтобы хранилище пакетов оставалось доступным только для чтения и было криптографически проверено.

### Как часто выходит HackerOS?
HackerOS выпускается по двухмесячному циклу. Издания Xfce, GNOME, Blue и Hydra выпускаются как версии x.0 и x.5. Издание LTS выходит только с релизами x.0, издание Gaming — с релизами x.3 и x.7, а издание Atomic — с релизами x.1 и x.9.

</details>

<details>
<summary><b>❓ Часто задаваемые вопросы (нажмите, чтобы развернуть)</b></summary>

**Где найти сайт H#?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**Где найти сайт bytes.io?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**Где найти сайт Hacker Lang?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**Где найти bit.io?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ CLI-инструменты HackerOS (нажмите, чтобы развернуть)</b></summary>

### hacker
Сердце HackerOS. Устанавливает дополнительное ПО и быстро обновляет всю систему (Flatpak, снапшоты, прошивки и APT).

### hl
Интерпретатор языка Hacker Lang.

### bit
Менеджер пакетов для Hacker Lang.

### h#
Компилятор и интерпретатор на основе LLVM для языка программирования H#.

### bytes
Менеджер пакетов для H#.

### virus
Менеджер пакетов для HackerScript.

### hackerc
Транспилятор/компилятор для HackerScript.

### hpm
Инструмент для работы с сообществом репозиториев, вдохновлённый `yay`.

### HackerOS Steam
Steam, работающий внутри контейнера Arch.

### getit
Альтернатива `wget`/`git`. Также можно использовать для загрузки отдельных каталогов с GitHub или GitLab.

### chker (choker)
CLI-инструмент для смены ядра системы — удаляет текущее ядро Debian и устанавливает собственное (XanMod или Liquorix).

### hup
Система автоматического обновления.

### hedit
Текстовый редактор, вдохновлённый Nano.

### ngt
Файловый менеджер в терминале (TUI) со встроенным текстовым редактором и консолью команд.

### isolator
В будущем будет доступен в издании Atomic. Позволяет запускать инструменты из нескольких контейнеров как обычные приложения, с собственным выделенным списком пакетов/репозиторием.

### hammer
Атомарный CLI-инструмент для издания HackerOS Atomic.

### bph
Инструмент для тестирования на проникновение, хорошо подходит для новичков.

### HexAI
ИИ-ассистент для HackerOS.

### HackerOS Builder
Специальная надстройка для live-сборки, упрощающая создание образов.

### GameFrame
Композитор, вдохновлённый Gamescope, для старых видеокарт.

</details>

<details>
<summary><b>📱 Приложения HackerOS (нажмите, чтобы развернуть)</b></summary>

### Hacker Term
Приложение терминала для HackerOS.

### HackerOS App
Приложение-компаньон для телефонов.

### HackerOS Game Mode
Активируется сочетанием Ctrl+G. Приложение, вдохновлённое Asus Armoury Crate.

### HackerOS Welcome
Приветственное приложение, отображаемое при первом запуске.

### Hacker Launcher
Предназначен в первую очередь для запуска приложений `.exe`.

### HackerOS Store
Устанавливайте лаунчеры игр, инструменты для тестирования на проникновение, драйверы и приложения.

</details>

<details>
<summary><b>🖥️ Сессии HackerOS (нажмите, чтобы развернуть)</b></summary>

### Hacker Mode
Сессия, использующая собственный композитор. Установите её командой `hacker unpack hacker-mode`.

### HackerOS TV
Сессия для просмотра медиаконтента. Установите её командой `hacker unpack hackeros-tv`.

### gamescope-session-steam
Выделенная сессия Steam (похожая на Bazzite или ChimeraOS), использующая контейнер HackerOS-Steam для Steam и Gamescope. Используется в издании Gaming.

### Cybersecurity Edition
Графическое окружение и выделенная сессия для издания Cybersecurity.

</details>

<details>
<summary><b>⚙️ Форматы конфигурации (нажмите, чтобы развернуть)</b></summary>

### .hk
Используется как формат библиотеки для Rust, H# и Hacker Lang.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
Документация по обоим форматам доступна здесь: [документация .hk и .hacker](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

Документацию по всем инструментам HackerOS можно найти здесь: [Документация инструментов HackerOS](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Скриншоты (нажмите, чтобы развернуть)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
