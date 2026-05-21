# Dotfiles
Clone this repo onto a new machine with the command:  
```
$ git clone --recurse-submodules git@github.com:ReezanVisram/dotfiles.git ~/dotfiles
```  
and use GNU Stow to set up configuration for Neovim and tmux.

Before proceeding, ensure `stow` is installed.

## Neovim Setup Instructions
1. Download Neovim from [source](https://github.com/neovim/neovim/releases). This config is for Neovim >= 0.12.
2. Install `git`, `make`, `unzip`, `gcc`, `ripgrep`, `fd-find`, `tree-sitter-cli`, `xclip`. Most of these can be installed from your package manager, but see [here](https://crates.io/crates/tree-sitter-cli) for installing `tree-sitter-cli`.
3. ```$ cd ~/dotfiles && stow nvim```
4. Launch neovim and ensure all plugins install correctly

## tmux Setup Instructions
1. Download tmux and build from [source](https://github.com/tmux/tmux)
2. ```$ cd ~/dotfiles && stow tmux```
3. Launch tmux and run `<prefix> + I` (`<prefix>` in this config is `<Ctrl>+<Space>`)
