# ddc-source-input

`input()` completion for ddc.vim

It works only for command line mode.

## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddc.vim

https://github.com/Shougo/ddc.vim

### getcmdcompltype() support

## Configuration

```vim
call ddc#custom#patch_global('sources', ['input'])

call ddc#custom#patch_global('sourceOptions', #{
      \   input: #{
      \     mark: 'input',
      \     isVolatile: v:true,
      \   }
      \ })
```
