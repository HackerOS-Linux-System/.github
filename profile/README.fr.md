# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — Basé sur Debian Testing

Une distribution Linux pour tout le monde. Jouez et apprenez le piratage éthique.

**🌐 Langue :**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 Les sections ci-dessous sont repliées. Cliquez sur **« ▶ Déplier »** pour chacune afin de continuer la lecture.

<details>
<summary><b>📦 Éditions de HackerOS (cliquez pour déplier)</b></summary>

## Official
L'édition standard de HackerOS. Destinée aux utilisateurs occasionnels et aux joueurs.

## Cybersecurity
Une édition orientée, de manière générale, vers la cybersécurité. Elle comprend un noyau dédié (HackerOS Kernel) optimisé pour les tâches de sécurité, un ensemble d'outils de cybersécurité propriétaires et, à l'avenir, un système de fichiers propriétaire nommé GhostFS. Basée sur Debian Stable.

## Cybersecurity Default
Une édition de HackerOS conçue exclusivement pour les équipes Red Team. En plus de tout ce que propose l'édition Cybersecurity standard, « Cybersecurity Default » inclut l'hyperviseur Xen ainsi qu'une session Red Team dédiée appelée « Penetration Mode ».

## NVIDIA
Une copie de l'édition Official avec les pilotes NVIDIA préinstallés.

### Xfce
Identique à l'édition Official, mais avec Xfce à la place de KDE.

### GNOME
Identique à l'édition Official, mais avec GNOME à la place de KDE.

### Hydra
Reprend (partiellement) l'apparence de Garuda Linux, et est identique à l'édition Official pour le reste.

### Blue
Une édition de HackerOS dotée d'un environnement graphique personnalisé.

## LTS
Identique à l'édition Official, mais construite sur Debian Stable plutôt que sur Debian Testing.

## Gaming
Une édition inspirée de SteamOS, avec le noyau XanMod LTS et un mode jeu similaire à celui de SteamOS.

## Atomic
L'édition immuable de HackerOS. Elle utilise des transactions de paquets atomiques : chaque opération crée une nouvelle génération (gen-N) stockée dans un magasin adressé par contenu. Les changements peuvent être activés immédiatement (mode utilisateur) ou après un redémarrage (mode système), avec prise en charge du retour arrière (rollback) via GRUB. Un gardien d'intégrité veille à ce que le magasin de paquets reste en lecture seule et vérifié cryptographiquement.

### À quelle fréquence HackerOS est-il publié ?
HackerOS suit un cycle de publication bimestriel. Les éditions Xfce, GNOME, Blue et Hydra sont publiées sous forme de versions x.0 et x.5. L'édition LTS n'est disponible qu'avec les versions x.0, l'édition Gaming avec les versions x.3 et x.7, et l'édition Atomic avec les versions x.1 et x.9.

</details>

<details>
<summary><b>❓ Foire aux questions (cliquez pour déplier)</b></summary>

**Où puis-je trouver le site de H# ?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**Où puis-je trouver le site de bytes.io ?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**Où puis-je trouver le site de Hacker Lang ?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**Où puis-je trouver bit.io ?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ Outils CLI de HackerOS (cliquez pour déplier)</b></summary>

### hacker
Le cœur de HackerOS. Installe des logiciels supplémentaires et met à jour rapidement l'ensemble du système (Flatpak, snapshots, firmware et APT).

### hl
Interpréteur pour Hacker Lang.

### bit
Gestionnaire de paquets pour Hacker Lang.

### h#
Compilateur et interpréteur basés sur LLVM pour le langage de programmation H#.

### bytes
Gestionnaire de paquets pour H#.

### virus
Gestionnaire de paquets pour HackerScript.

### hackerc
Transpileur/compilateur pour HackerScript.

### hpm
Outil de dépôt communautaire inspiré de `yay`.

### HackerOS Steam
Steam exécuté dans un conteneur Arch.

### getit
Une alternative à `wget`/`git`. Peut aussi être utilisé pour télécharger des répertoires individuels depuis GitHub ou GitLab.

### chker (choker)
Outil CLI pour changer le noyau du système — supprime le noyau Debian actuel et en installe un personnalisé (XanMod ou Liquorix).

### hup
Système de mise à jour automatique.

### hedit
Éditeur de texte inspiré de Nano.

### ngt
Un gestionnaire de fichiers en mode terminal (TUI), avec éditeur de texte et console de commandes intégrés.

### isolator
Sera disponible sur l'édition Atomic à l'avenir. Permet d'exécuter des outils provenant de plusieurs conteneurs comme des applications normales, avec sa propre liste de paquets/dépôt dédié.

### hammer
Outil CLI atomique pour l'édition HackerOS Atomic.

### bph
Outil de tests d'intrusion, bien adapté aux débutants.

### HexAI
Assistant IA pour HackerOS.

### HackerOS Builder
Surcouche spéciale de live-build facilitant la création d'images.

### GameFrame
Un compositeur inspiré de Gamescope pour les cartes graphiques plus anciennes.

</details>

<details>
<summary><b>📱 Applications HackerOS (cliquez pour déplier)</b></summary>

### Hacker Term
Application de terminal pour HackerOS.

### HackerOS App
Application compagnon pour smartphones.

### HackerOS Game Mode
Activé avec Ctrl+G. Une application inspirée d'Asus Armoury Crate.

### HackerOS Welcome
L'application d'accueil affichée au premier démarrage.

### Hacker Launcher
Conçu principalement pour exécuter des applications `.exe`.

### HackerOS Store
Installez des lanceurs de jeux, des outils de tests d'intrusion, des pilotes et des applications.

</details>

<details>
<summary><b>🖥️ Sessions HackerOS (cliquez pour déplier)</b></summary>

### Hacker Mode
Une session utilisant son propre compositeur. Installez-la avec `hacker unpack hacker-mode`.

### HackerOS TV
Une session dédiée au visionnage multimédia. Installez-la avec `hacker unpack hackeros-tv`.

### gamescope-session-steam
Une session Steam dédiée (similaire à Bazzite ou ChimeraOS) utilisant le conteneur HackerOS-Steam pour Steam et Gamescope. Utilisée dans l'édition Gaming.

### Cybersecurity Edition
L'environnement graphique ainsi qu'une session dédiée pour l'édition Cybersecurity.

</details>

<details>
<summary><b>⚙️ Formats de configuration (cliquez pour déplier)</b></summary>

### .hk
Utilisé comme format de bibliothèque pour Rust, H# et Hacker Lang.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
La documentation des deux formats est disponible ici : [documentation .hk et .hacker](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

La documentation de tous les outils HackerOS se trouve ici : [Documentation des outils HackerOS](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Captures d'écran (cliquez pour déplier)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
