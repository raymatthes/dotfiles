set tabstop=4
set expandtab
filetype indent on
set autoindent

"syntax highlighting
syntax enable

"line numbers off/on
"set nonumber
set number

"display white space characters as codes
"set list
set nolist

"put .swp files in /tmp"
set directory=/tmp

"status line"
set statusline=%t\ %y\ format:\ %{&ff};\ [%c,%l]
set laststatus=2

" Press F4 to toggle highlighting on/off, and show current value.
:noremap <F4> :set hlsearch! hlsearch?<CR>

" Python stuff start
"
" Press F5 to run python
autocmd FileType python nnoremap <buffer> <F5> :exec '!clear; python' shellescape(@%, 1)<cr>

au BufNewFile,BufRead *.py
    \ set tabstop=4 |
    \ set softtabstop=4 |
    \ set shiftwidth=4 |
    \ set textwidth=79 |
    \ set expandtab |
    \ set autoindent |
    \ set fileformat=unix |

" C/C++ stuff
au BufNewFile,BufRead *.c,*.cpp,*.h,Makefile,makefile
    \ set tabstop=2 |
    \ set softtabstop=0 |
    \ set shiftwidth=2 |
    \ set textwidth=79 |
    \ set expandtab |
    \ set autoindent |
    \ set fileformat=unix |
    \ set smarttab |

" define BadWhitespace before using in a match
highlight BadWhitespace ctermbg=red guibg=darkred
au BufRead,BufNewFile *.py,*.pyw,*.c,*.h,*.java,*.groovy,*.gsp,*.xml,*.js,*.html,*.css,*.json,*.rb match BadWhitespace /\s\+$/

set encoding=utf-8

" Python stuff end

au BufNewFile,BufRead *.js,*.html,*.css,*.java,*.groovy,*.gsp,*.xml,*.json,*.rb
    \ set tabstop=3 |
    \ set softtabstop=3 |
    \ set shiftwidth=3 |

autocmd Filetype html setlocal ts=2 sts=2 sw=2
autocmd Filetype ruby setlocal ts=2 sts=2 sw=2
autocmd Filetype javascript setlocal ts=2 sts=2 sw=2
autocmd Filetype java setlocal ts=3 sts=3 sw=3
autocmd Filetype groovy setlocal ts=3 sts=3 sw=3
autocmd Filetype gradle setlocal ts=3 sts=3 sw=3

" display keystrokes
set showcmd

if has('gui_running')
	set background=dark
	colorscheme elflord
else
	colorscheme elflord
endif

set guifont=Menlo\ Regular:h14

" Access to clipboard
"set clipboard=unnamed

set incsearch

