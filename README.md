# Configuració de Mac OS X

Quan haig de configurar un nou mac (o un que hem formatejat), aquí tinc la llista de les aplicacions bàsiques que necessitaré tenir-hi instal·lades.

## Homebrew

El gestor de paquest és el primer que instal·lo, ja que és l'eina bàsica per instal·lar la resta de les aplicacions.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Mac App Store

CLI per poder descarregar aplicacions directament des de la terminal sempre que hagin estat comprades previament a la Mac App Store.

```bash
brew install mas
```

## Llistat d'aplicacions

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
#
brew install node
brew install yarn
brew install derailed/k9s/k9s

# Proxies
brew install charles
brew install proxyman

# API Client
brew install --cask yaak
brew install --cask postman

# Hugo
brew install hugo

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
