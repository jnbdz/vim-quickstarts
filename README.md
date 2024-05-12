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
