# ddc-input

`input()` completion for ddc.vim

It works only for command line mode.


## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddc.vim

https://github.com/Shougo/ddc.vim

### getcmdcompletion() support

## Configuration

```vim
" Use input source.
call ddc#custom#patch_global('sources', ['input'])

" Change source options
call ddc#custom#patch_global('sourceOptions', {
      \   'input': {
      \     'mark': 'input',
      \     'isVolatile': v:true,
      \   }
      \ })
```
