# Configuració de Mac OS X

Davant la configuració d’una nova màquina (o la necessitat de tornar a instal·lar desrpés de formatejar), aquí hi ha una llista molt breu i bàsica dels sospitosos habituals, relacionada amb la configuració d’un ordinador Mac per desenvolupar i frikejar.

## Homebrew i Cask

El gestor de paquets és el primer que sempre instal·lo. Simplement seguint els passos indicats. Descàrrega i instal·la les eines de la línia d’ordres per a Xcode. Homebrew Cask s’implementa com a part de Homebrew, de manera que estan habilitats des del primer moment. Finalment, Brew-Cask-Upgrade proporciona capacitats similars a la actualització a Cask, i estem tots preparats.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew tap buo/cask-upgrade
```

## Mac App Store

CLI per poder descarregar aplicacions directament des de la terminal. Només cal instal·lar-lo i ja està.

```bash
brew install mas
```

## Llista d'aplicacions a instal·lar

Un cop instal·lat Homebrew, és el moment de descarregar les aplicacions que necessitem. La llista d’aplicacions és la següent:


### Terminal i relacionats

```bash
# Git
brew install git

# Terminal
brew install hyper
brew install warp

# Add-ons de la terminal
brew install starship
brew install wget
brew install zsh
brew install zsh-completions
brew install zsh-autosuggestions
brew install zsh-syntax-highlighting
```

### Navegadors

```bash
# Navegadors
brew install brave-browser
brew install firefox
brew install google-chrome
```

### Desenvolupament

```bash
# Proxies
brew install charles
brew install proxyman

# DevOps
brew install packer
brew install terraform

# IDEs
brew install visual-studio-code

# VPN
brew install nextdns
brew install tailscale
```

### Utilitats

```bash
brew install appcleaner
brew install bitwarden

# Missatgeria
brew install discord

# Screen recording
brew install kap

# Productivitat i notes
brew install meetingbar
brew install notion
brew install obsidian
brew install raycast

# Slicer impressora 3D
brew install orcaslicer

# Disseny
# Pixelmator
mas install 1289583905
brew install figma

# Unarchiver
brew install the-unarchiver

# Audio i video
brew install spotify
brew install vlc
```

El gestor de la barra de menus no es pot instal·lar des de brew així que toca descarregar-lo manualment:

```bash
https://icemenubar.app/
```

### Fonts

```bash
brew install --cask font-inter
```