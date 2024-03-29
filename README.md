# Starship zsh plugin

This ZSH plugin initializes the [Starship prompt](https://starship.rs) - a minimal, blazing-fast and infinitely customizable cross-shell prompt.

[Demo](https://user-images.githubusercontent.com/62098008/169764279-50b48262-9506-4651-ba89-f6611a88ebf0.mp4)

# Installation

**Note:** you have to [install starship](https://starship.rs/guide/#%F0%9F%9A%80-installation) first.

Add one of the following to your `.zshrc` file depending on your package manager:

## [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh)

1. Add `starship` to the plugins array in your `.zshrc` file:

```zsh
plugins=(... starship)
```

> ⚠️ NOTE: this plugin unsets your ZSH_THEME variable

## [antigen](https://github.com/zsh-users/antigen)

1. Add the following to your `.zshrc` file:

```zsh
antigen bundle axieax/zsh-starship
```

## Manual (Git Clone)

1. Clone this repository somewhere on your machine. This guide will assume `~/.zsh/zsh-starship`, although other locations are possible.

```bash
git clone https://github.com/axieax/zsh-starship.git ~/.zsh/zsh-starship
```

2. Add the following to your `.zshrc` file:

```zsh
source ~/.zsh/zsh-starship/starship.plugin.zsh
```
