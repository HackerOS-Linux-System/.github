# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — Basado en Debian Testing

Una distribución de Linux para todos. Juega y aprende hacking ético.

**🌐 Idioma:**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 Las siguientes secciones están contraídas. Haz clic en **«▶ Expandir»** en cada una para seguir leyendo.

<details>
<summary><b>📦 Ediciones de HackerOS (clic para expandir)</b></summary>

## Official
La edición estándar de HackerOS. Pensada para usuarios casuales y jugadores.

## Cybersecurity
Una edición orientada, en general, a la ciberseguridad. Incluye un kernel dedicado (HackerOS Kernel) optimizado para tareas de seguridad, un conjunto de herramientas de ciberseguridad propietarias y, en el futuro, un sistema de archivos propietario llamado GhostFS. Basada en Debian Stable.

## Cybersecurity Default
Una edición de HackerOS diseñada exclusivamente para equipos Red Team. Además de todo lo incluido en la edición estándar Cybersecurity, «Cybersecurity Default» incorpora el hipervisor Xen y una sesión Red Team dedicada conocida como «Penetration Mode».

## NVIDIA
Una copia de la edición Official con controladores NVIDIA preinstalados.

### Xfce
Igual que la edición Official, pero con Xfce en lugar de KDE.

### GNOME
Igual que la edición Official, pero con GNOME en lugar de KDE.

### Hydra
Tiene (parcialmente) el aspecto de Garuda Linux y, por lo demás, es idéntica a la edición Official.

### Blue
Una edición de HackerOS con un entorno gráfico personalizado.

## LTS
Igual que la edición Official, pero basada en Debian Stable en lugar de Debian Testing.

## Gaming
Una edición inspirada en SteamOS, con el kernel XanMod LTS y un modo de juego similar al de SteamOS.

## Atomic
La edición inmutable de HackerOS. Utiliza transacciones de paquetes atómicas, donde cada operación crea una nueva generación (gen-N) almacenada en un almacén direccionado por contenido. Los cambios pueden activarse de inmediato (modo usuario) o tras reiniciar (modo sistema), con soporte de reversión (rollback) mediante GRUB. Un guardián de integridad garantiza que el almacén de paquetes permanezca de solo lectura y verificado criptográficamente.

### ¿Con qué frecuencia se publica HackerOS?
HackerOS sigue un ciclo de publicación bimensual. Las ediciones Xfce, GNOME, Blue e Hydra se publican como versiones x.0 y x.5. La edición LTS se publica solo con las versiones x.0, la edición Gaming con las versiones x.3 y x.7, y la edición Atomic con las versiones x.1 y x.9.

</details>

<details>
<summary><b>❓ Preguntas frecuentes (clic para expandir)</b></summary>

**¿Dónde encuentro el sitio de H#?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**¿Dónde encuentro el sitio de bytes.io?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**¿Dónde encuentro el sitio de Hacker Lang?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**¿Dónde encuentro bit.io?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ Herramientas CLI de HackerOS (clic para expandir)</b></summary>

### hacker
El corazón de HackerOS. Instala software adicional y actualiza todo el sistema rápidamente (Flatpak, instantáneas, firmware y APT).

### hl
Intérprete de Hacker Lang.

### bit
Gestor de paquetes para Hacker Lang.

### h#
Compilador e intérprete basado en LLVM para el lenguaje de programación H#.

### bytes
Gestor de paquetes para H#.

### virus
Gestor de paquetes para HackerScript.

### hackerc
Transpilador/compilador para HackerScript.

### hpm
Herramienta de repositorio comunitario inspirada en `yay`.

### HackerOS Steam
Steam ejecutándose dentro de un contenedor Arch.

### getit
Una alternativa a `wget`/`git`. También se puede usar para descargar directorios individuales desde GitHub o GitLab.

### chker (choker)
Herramienta CLI para cambiar el kernel del sistema: elimina el kernel de Debian actual e instala uno personalizado (XanMod o Liquorix).

### hup
Sistema de actualización automática.

### hedit
Editor de texto inspirado en Nano.

### ngt
Un gestor de archivos basado en terminal (TUI) con editor de texto y consola de comandos integrados.

### isolator
Estará disponible en la edición Atomic en el futuro. Permite ejecutar herramientas de varios contenedores como aplicaciones normales, con su propia lista de paquetes/repositorio dedicado.

### hammer
Herramienta CLI atómica para la edición HackerOS Atomic.

### bph
Herramienta de pruebas de penetración, adecuada para principiantes.

### HexAI
Asistente de IA para HackerOS.

### HackerOS Builder
Capa especial de compilación en vivo para facilitar la creación de imágenes.

### GameFrame
Un compositor inspirado en Gamescope para tarjetas gráficas más antiguas.

</details>

<details>
<summary><b>📱 Aplicaciones de HackerOS (clic para expandir)</b></summary>

### Hacker Term
Aplicación de terminal para HackerOS.

### HackerOS App
Aplicación complementaria para teléfonos.

### HackerOS Game Mode
Se activa con Ctrl+G. Una aplicación inspirada en Asus Armoury Crate.

### HackerOS Welcome
La aplicación de bienvenida que se muestra en el primer arranque.

### Hacker Launcher
Diseñado principalmente para ejecutar aplicaciones `.exe`.

### HackerOS Store
Instala lanzadores de juegos, herramientas de pruebas de penetración, controladores y aplicaciones.

</details>

<details>
<summary><b>🖥️ Sesiones de HackerOS (clic para expandir)</b></summary>

### Hacker Mode
Una sesión que usa su propio compositor. Instálala con `hacker unpack hacker-mode`.

### HackerOS TV
Una sesión para ver contenido multimedia. Instálala con `hacker unpack hackeros-tv`.

### gamescope-session-steam
Una sesión dedicada de Steam (similar a Bazzite o ChimeraOS) que usa el contenedor HackerOS-Steam para Steam y Gamescope. Se usa en la edición Gaming.

### Cybersecurity Edition
El entorno gráfico y una sesión dedicada para la edición Cybersecurity.

</details>

<details>
<summary><b>⚙️ Formatos de configuración (clic para expandir)</b></summary>

### .hk
Se usa como formato de biblioteca para Rust, H# y Hacker Lang.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
La documentación de ambos formatos está disponible aquí: [documentación de .hk y .hacker](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

La documentación de todas las herramientas de HackerOS se encuentra aquí: [Documentación de herramientas de HackerOS](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Capturas de pantalla (clic para expandir)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
