# Dotfiles

My personal dotfiles – configuration files for shell, editors, tools, and other environments. Maintained for easy replication and sharing of my workflows across devices.

## Contents

- Shell configuration: `.bashrc`, `.zshrc`, etc.
- Editor settings: `.vimrc`, `.config/nvim/`, etc.
- Git configuration: `.gitconfig`, `.gitignore_global`
- Tmux settings: `.tmux.conf`
- Other tools: e.g. `alacritty`, `starship`, `fzf`, etc.

## Installation

```bash
git clone https://github.com/<your-username>/dotfiles.git ~/dotfiles
cd ~/dotfiles
./install.sh
```
Or follow the instructions in the installation script.

## Overview

| Folder / File        | Description                       |
|----------------------|-----------------------------------|
| `.bashrc`, `.zshrc`  | Shell configuration               |
| `.vimrc`             | Vim/Neovim settings               |
| `.gitconfig`         | Global Git configuration          |
| `.tmux.conf`         | Tmux configuration                |
| `install.sh`         | Installation/automation script    |

## Notes

- This repository never contains sensitive data (passwords, private keys, API tokens, etc.).
- For machine-specific settings, use `*.local` files, which are included in `.gitignore`.
- All files are commented for easier editing and understanding.

## License

MIT

---
