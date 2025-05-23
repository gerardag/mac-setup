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
brew install --cask \
  git \
  hyper \
  starship \
  wget \
  zsh \
  zsh-completions \
  zsh-autosuggestions \
  zsh-syntax-highlighting \
```

### Navegadors

```bash
brew install --cask \
  firefox \
  google-chrome \
```

### Desenvolupament

```bash
brew install --cask \
  charles \
  packer \
  proxyman \
  terraform \
  visual-studio-code \

# Tailscale and nextdns
brew install nextdns
brew install tailscale
```

### Utilitats

```bash
brew install --cask \
  alacritty \
  appcleaner \
  bitwarden \
  discord \
  figma \
  kap \
  obsidian \
  orcaslicer
  raycast \
  spotify \
  the-unarchiver \
  vlc \
```

```bash
# Pixelmator
mas install 1289583905
```

El gestor de la barra de menus no es pot instal·lar des de brew així que toca descarregar-lo manualment:

```bash
https://icemenubar.app/
```

### Fonts

```bash
brew install --cask font-inter
```