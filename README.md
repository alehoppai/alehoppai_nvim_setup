# NeoVim config

Created mainly for WSL Ubuntu 22.04 LTS. Based on [this guide](https://martinlwx.github.io/en/config-neovim-from-scratch/) and updated for my needs. Basically I'm gonna use this setup on all machines I need.


## Neovim version

This setup requires unstable neovim version. To do so, perform following steps:
- `sudo add-apt-repository ppa:neovim-ppa/unstable`
- `sudo apt-get update`
- `sudo apt-get install neovim`

## Requirements

- Node.js & npm
- [Packer.vim](https://github.com/wbthomason/packer.nvim). With this setup installer will automaticall after saving `lua/plugins.lua`
- `[sudo] npm install -g typescript typescript-language-server`

## Colorscheme

To change colorscheme add required theme to `lua/plugins.lua` and follow `packer.vim` syntax. Majority of colorschemes can be browsed [Here](https://github.com/topics/neovim-colorscheme) or use your favourite search engine.

## Notes

Pls pay attention to `lua/keymaps.lua` because some default keybindings were changed.

