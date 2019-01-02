# [spf13-vim](https://github.com/spf13/spf13-vim)



## Install
### Install spf13-vim
```
cd ~/
curl https://j.mp/spf13-vim3 -L > spf13-vim.sh && sh spf13-vim.sh
```
### Clone my customized spf13-vim
```
git clone git@github.com:keer2345/.spf13-vim-3-myself.git

rm spf13-vim.sh
rm ~/.vimrc.local
rm ~/.vimrc.before.local
rm ~/.vimrc.bundles.local
rm ~/.vimrc.local.plugin
ln -s ~/.spf13-vim-3-myself/.vimrc.local ~/.vimrc.local
ln -s ~/.spf13-vim-3-myself/.vimrc.before.local ~/.vimrc.before.local
ln -s ~/.spf13-vim-3-myself/.vimrc.bundles.local ~/.vimrc.bundles.local
ln -s ~/.spf13-vim-3-myself/.vimrc.local.plugin ~/.vimrc.local.plugin

sudo apt install vim-gnome
```

## Configuration
```
~/.spf13-vim-3-myself/.vimrc.local
~/.spf13-vim-3-myself/.vimrc.local.plugin
~/.spf13-vim-3-myself/.vimrc.before.local
```

## Plugins
```
~/.spf13-vim-3-myself/.vimrc.bundles.local
```


### Utility
#### vim-scripts/BufOnly.vim
- `:BufOnly` without an argument will unload all buffers but the current one.
- `:BufOnly` with an argument will close all buffers but the supplied buffer name/number
#### SirVer/ultisnips
#### junegunn/fzf.vim
#### junegunn/fzf
#### godlygeek/tabular
#### ctrlpvim/ctrlp.vim
#### benmills/vimux
Easily interact with tmux from vim.
#### jeetsukumaran/vim-buffergator
#### gilsondev/searchtasks.vim
#### Shougo/neocomplete.vim
- `C-k`: to select-and-expand a snippet from the Neocomplcache popup (Use C-n and C-p to select it). C-k can also be used to jump to the next field in the snippet.
- `Tab`: to select the next field to fill in the snippet.
#### tpope/vim-dispatch
#### jceb/vim-orgmode
#### tpope/vim-speeddating

### Generic Programming Support 
#### honza/vim-snippets
#### tomtom/tcomment_vim
#### maksimr/vim-jsbeautify
#### scrooloose/syntastic
#### neomake/neomake
Neomake is a plugin for Vim/Neovim to asynchronously run programs.
#### tpope/vim-fugitive

### Erlang
#### vim-erlang/vim-erlang-tags
#### vim-erlang/vim-erlang-runtime
#### vim-erlang/vim-erlang-omnicomplete
#### vim-erlang/vim-erlang-compiler

### Elixir
#### elixir-lang/vim-elixir
#### avdgaag/vim-phoenix
#### mmorearty/elixir-ctags
#### mattreduce/vim-mix
#### BjRo/vim-extest
#### frost/vim-eh-docs
#### slashmili/alchemist.vim
#### tpope/vim-endwise
#### jadercorrea/elixir_generator.vim
#### mhinz/vim-mix-format

### Python
- `F6`: Format source with flake8
- `,r`: Run python

### Markdown / Writting
#### reedes/vim-pencil
#### iamcco/markdown-preview.vim
- `,mp`: Start Markdown Preview
- `,ms`: Stop Markdown Preview
#### mzlogin/vim-markdown-toc
- `:GenToGFM`: Generater the markdown catalog
- `:UpdateToc`: Update the markdown catalog


### Chiel92/vim-autoformat
Provide easy code formatting in Vim by integrating existing code formatters.
- `F7` Autoformat
