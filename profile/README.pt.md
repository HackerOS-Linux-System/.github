# ![HackerOS Linux System based on Debian Testing.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/addons/watermark.png)

# HackerOS — Baseado no Debian Testing

Uma distribuição Linux para todos. Jogue e aprenda hacking ético.

**🌐 Idioma:**
[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Polski](https://img.shields.io/badge/lang-Polski-white)](README.pl.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-yellow)](README.de.md)
[![Español](https://img.shields.io/badge/lang-Español-red)](README.es.md)
[![Français](https://img.shields.io/badge/lang-Français-blue)](README.fr.md)
[![Русский](https://img.shields.io/badge/lang-Русский-lightgrey)](README.ru.md)
[![Português](https://img.shields.io/badge/lang-Português-green)](README.pt.md)
[![中文](https://img.shields.io/badge/lang-中文-orange)](README.zh.md)

> 💡 As seções abaixo estão recolhidas. Clique em **"▶ Expandir"** em cada uma para continuar lendo.

<details>
<summary><b>📦 Edições do HackerOS (clique para expandir)</b></summary>

## Official
A edição padrão do HackerOS. Destinada a usuários casuais e jogadores.

## Cybersecurity
Uma edição voltada, de forma geral, para a cibersegurança. Possui um kernel dedicado (HackerOS Kernel) otimizado para tarefas de segurança, um conjunto de ferramentas de cibersegurança proprietárias e, no futuro, um sistema de arquivos proprietário chamado GhostFS. Baseada no Debian Stable.

## Cybersecurity Default
Uma edição do HackerOS projetada exclusivamente para equipes Red Team. Além de tudo o que está presente na edição Cybersecurity padrão, a "Cybersecurity Default" inclui o Hypervisor Xen e uma sessão Red Team dedicada, conhecida como "Penetration Mode".

## NVIDIA
Uma cópia da edição Official com drivers NVIDIA pré-instalados.

### Xfce
Igual à edição Official, porém com Xfce em vez de KDE.

### GNOME
Igual à edição Official, porém com GNOME em vez de KDE.

### Hydra
Tem (parcialmente) a aparência do Garuda Linux e, fora isso, é idêntica à edição Official.

### Blue
Uma edição do HackerOS com um ambiente gráfico personalizado.

## LTS
Igual à edição Official, mas construída sobre o Debian Stable em vez do Debian Testing.

## Gaming
Uma edição inspirada no SteamOS, com o kernel XanMod LTS e um modo de jogo semelhante ao do SteamOS.

## Atomic
A edição imutável do HackerOS. Utiliza transações de pacotes atômicas, em que cada operação cria uma nova geração (gen-N) armazenada em um repositório endereçado por conteúdo. As alterações podem ser ativadas imediatamente (modo usuário) ou após uma reinicialização (modo sistema), com suporte a rollback via GRUB. Um guardião de integridade garante que o repositório de pacotes permaneça somente leitura e criptograficamente verificado.

### Com que frequência o HackerOS é lançado?
O HackerOS segue um ciclo de lançamento bimestral. As edições Xfce, GNOME, Blue e Hydra são lançadas como versões x.0 e x.5. A edição LTS é lançada apenas com as versões x.0, a edição Gaming com as versões x.3 e x.7, e a edição Atomic com as versões x.1 e x.9.

</details>

<details>
<summary><b>❓ Perguntas frequentes (clique para expandir)</b></summary>

**Onde encontro o site do H#?**
[https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/h-sharp/docs.html)

**Onde encontro o site do bytes.io?**
[https://bytes-repository.github.io/website/](https://bytes-repository.github.io/website/)

**Onde encontro o site do Hacker Lang?**
[https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html](https://hackeros-linux-system.github.io/HackerOS-Website/hacker-lang/docs.html)

**Onde encontro o bit.io?**
[https://bit-io.github.io/website/](https://bit-io.github.io/website/)

</details>

<details>
<summary><b>🛠️ Ferramentas de CLI do HackerOS (clique para expandir)</b></summary>

### hacker
O coração do HackerOS. Instala software adicional e atualiza todo o sistema rapidamente (Flatpak, snapshots, firmware e APT).

### hl
Interpretador para Hacker Lang.

### bit
Gerenciador de pacotes para Hacker Lang.

### h#
Compilador e interpretador baseados em LLVM para a linguagem de programação H#.

### bytes
Gerenciador de pacotes para H#.

### virus
Gerenciador de pacotes para HackerScript.

### hackerc
Transpilador/compilador para HackerScript.

### hpm
Ferramenta de repositório comunitário inspirada no `yay`.

### HackerOS Steam
Steam executado dentro de um contêiner Arch.

### getit
Uma alternativa ao `wget`/`git`. Também pode ser usada para baixar diretórios individuais do GitHub ou GitLab.

### chker (choker)
Ferramenta de CLI para trocar o kernel do sistema — remove o kernel Debian atual e instala um personalizado (XanMod ou Liquorix).

### hup
Sistema de atualização automática.

### hedit
Editor de texto inspirado no Nano.

### ngt
Um gerenciador de arquivos baseado em terminal (TUI), com editor de texto e console de comandos integrados.

### isolator
Estará disponível na edição Atomic no futuro. Permite executar ferramentas de vários contêineres como aplicativos normais, com sua própria lista de pacotes/repositório dedicado.

### hammer
Ferramenta de CLI atômica para a edição HackerOS Atomic.

### bph
Ferramenta de testes de penetração, bem adequada para iniciantes.

### HexAI
Assistente de IA para o HackerOS.

### HackerOS Builder
Camada especial de live-build para facilitar a criação de imagens.

### GameFrame
Um compositor inspirado no Gamescope para placas de vídeo mais antigas.

</details>

<details>
<summary><b>📱 Aplicativos do HackerOS (clique para expandir)</b></summary>

### Hacker Term
Aplicativo de terminal para o HackerOS.

### HackerOS App
Aplicativo complementar para celulares.

### HackerOS Game Mode
Ativado com Ctrl+G. Um aplicativo inspirado no Asus Armoury Crate.

### HackerOS Welcome
O aplicativo de boas-vindas exibido na primeira inicialização.

### Hacker Launcher
Projetado principalmente para executar aplicativos `.exe`.

### HackerOS Store
Instale lançadores de jogos, ferramentas de testes de penetração, drivers e aplicativos.

</details>

<details>
<summary><b>🖥️ Sessões do HackerOS (clique para expandir)</b></summary>

### Hacker Mode
Uma sessão que usa seu próprio compositor. Instale-a com `hacker unpack hacker-mode`.

### HackerOS TV
Uma sessão para assistir a conteúdo multimídia. Instale-a com `hacker unpack hackeros-tv`.

### gamescope-session-steam
Uma sessão dedicada do Steam (semelhante à Bazzite ou ChimeraOS), que usa o contêiner HackerOS-Steam para Steam e Gamescope. Usada na edição Gaming.

### Cybersecurity Edition
O ambiente gráfico e uma sessão dedicada para a edição Cybersecurity.

</details>

<details>
<summary><b>⚙️ Formatos de configuração (clique para expandir)</b></summary>

### .hk
Usado como formato de biblioteca para Rust, H# e Hacker Lang.

[crates.io](https://crates.io/crates/hk-parser)

### .hacker
A documentação de ambos os formatos está disponível aqui: [documentação de .hk e .hacker](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/hk.html)

A documentação de todas as ferramentas do HackerOS pode ser encontrada aqui: [Documentação das ferramentas do HackerOS](https://hackeros-linux-system.github.io/HackerOS-Website/tools-docs/index.html)

</details>

<details>
<summary><b>🖼️ Capturas de tela (clique para expandir)</b></summary>

![HackerOS Official.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/official-edition.png)

![HackerOS Hydra.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/hydra-edition.png)

![HackerOS Gnome.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gnome-edition.png)

![HackerOS Xfce.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/xfce-edition.png)

![HackerOS Gaming.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/gaming-edition.png)

![HackerOS Blue.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/blue-edition.png)

![HackerOS Cybersecurity.](https://raw.githubusercontent.com/HackerOS-Linux-System/HackerOS-Website/main/cybersecurity-edition-edition.png)

</details>
