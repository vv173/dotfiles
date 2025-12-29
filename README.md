# About
This repository contains configuration files for tools that I use daily and provision on each Linux machine that I use.

# Installation
Clone the repo
```bash
git clone https://github.com/vv173/dotfiles.git
cd dotfiles
```

I manage dotfiles with GNU Stow. Provision can be done with single command:
```bash
stow *
```
or link only selected packages:
```bash
stow bash vim
```

# Components
- vim
- tmux
- bash
- starship
- git
