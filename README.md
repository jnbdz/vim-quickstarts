# vim-quickstarts
Vim | Quickstarts

## Copy & Paste (clipboard)
```vim
:w !xclip -selection clipboard
```
or for the selected text only: 
```vim
:'<,'>w !xclip -selection clipboard
```

Mapping: 

```vim
" Copy entire buffer to clipboard
nnoremap <leader>c :w !xclip -selection clipboard<CR>

" Copy selected text to clipboard
vnoremap <leader>c :w !xclip -selection clipboard<CR>
```
