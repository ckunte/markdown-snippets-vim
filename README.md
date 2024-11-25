# Blog snippets for Vim and Neovim

This repository contains a couple of snippets that reduces the tedium of adding html blocks to a minimum.

## Requirements

- Vim or Neovim with python3 support
- UltiSnips
- blog-snippets-vim

## Installation

Add the following to `.vimrc` file (for vim-plug manager), reload, and install the plug-in (with `:PlugInstall`):

```vim
call plug#begin()

Plug 'ckunte/blog-snippets-vim'

call plug#end()

let g:UltiSnipsExpandTrigger = '<tab>'
let g:UltiSnipsJumpForwardTrigger = '<c-j>'
let g:UltiSnipsJumpBackwardTrigger = '<c-k>'
```

