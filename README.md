# starship plugin

Initializes [starship prompt](https://starship.rs) - a minimal, blazing-fast and infinitely customizable cross-shell prompt.

![Demo](https://starship.rs/demo.webm)

# Installation

**Note:** you have to [install starship](https://starship.rs/guide/#%F0%9F%9A%80-installation) first.

Add one of the following to your `.zshrc` file depending on your package manager:

[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

Clone this repository

`git clone https://github.com/axieax/zsh-starship.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/starship`

To use it, add `starship` to the plugins array in your `.zshrc` file:

```zsh
plugins=(... starship)
```
