`~/.vimrc`

```sh
" Prevent line wrapping
set nowrap

" Use smart indentation
set smarttab
set smartindent
set autoindent

" Convert tabs to spaces
set expandtab

" Number of spaces a tab counts for
set tabstop=4

" Number of spaces used for each indentation level
set shiftwidth=4

" Make backspace behave more naturally
set backspace=indent,eol,start

" === General Vim Settings ===
syntax on
set background=dark

" Optional: Better visuals
set number
set cursorline

" Show relative line numbers
set relativenumber

set background=dark
colorscheme gruvbox
let g:gruvbox_contrast_dark = 'medium' " or 'hard' or 'soft'
let g:gruvbox_invert_selection = '0'

set mouse=a
```
