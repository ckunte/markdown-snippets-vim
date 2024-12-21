# Markdown snippets for Vim and Neovim

This repository contains a couple of snippets (used for a blog) that reduces the tedium of adding html blocks to a minimum.

## Requirements

- Vim or Neovim with python3 support
- [UltiSnips]
- [markdown-snippets-vim]

## Installation

Add the following to `.vimrc` file (for vim-plug manager), reload, and install the plug-in (with `:PlugInstall`):

```vim
call plug#begin()

Plug 'sirver/ultisnips'
Plug 'ckunte/markdown-snippets-vim'

call plug#end()

let g:UltiSnipsExpandTrigger = '<tab>'
let g:UltiSnipsJumpForwardTrigger = '<c-j>'
let g:UltiSnipsJumpBackwardTrigger = '<c-k>'
```
[UltiSnips]: https://github.com/SirVer/ultisnips
[markdown-snippets-vim]: https://github.com/ckunte/markdown-snippets-vim
