# [spf13-vim](https://github.com/spf13/spf13-vim)


<!-- vim-markdown-toc GFM -->

* [Install](#install)
    * [Install spf13-vim](#install-spf13-vim)
    * [Clone my customized spf13-vim](#clone-my-customized-spf13-vim)
* [Plugin](#plugin)
* [Feature](#feature)
    * [Python](#python)
    * [Markdown](#markdown)
    * [Shougo/neosnippet.vim](#shougoneosnippetvim)
    * [Chiel92/vim-autoformat](#chiel92vim-autoformat)

<!-- vim-markdown-toc -->

## Install
### Install spf13-vim
```
cd ~/
curl https://j.mp/spf13-vim3 -L > spf13-vim.sh && sh spf13-vim.sh
```
### Clone my customized spf13-vim
```
git clone git@github.com:keer2345/.spf13-vim-3-myself.git

ln -s ~/.spf13-vim-3-myself/.vimrc.local ~/.vimrc.local
ln -s ~/.spf13-vim-3-myself/.vimrc.before.local ~/.vimrc.before.local
ln -s ~/.spf13-vim-3-myself/.vimrc.bundles.local ~/.vimrc.bundles.local
```

## Plugin
```
~/.spf13-vim-3-myself/.vimrc.bundles.local
```
## Feature
```
~/.spf13-vim-3-myself/.vimrc.local
~/.spf13-vim-3-myself/.vimrc.before.local
```
### Python
- `F6`: Format source with flake8
- `,r`: Run python

### Markdown
- `,mp`: Start Markdown Preview
- `,ms`: Stop Markdown Preview
- `:GenToGFM`: Generater the markdown catalog
- `:UpdateToc`: Update the markdown catalog
### Shougo/neosnippet.vim
- `C-k`: to select-and-expand a snippet from the Neocomplcache popup (Use C-n and C-p to select it). C-k can also be used to jump to the next field in the snippet.
- `Tab`: to select the next field to fill in the snippet.

### Chiel92/vim-autoformat
Provide easy code formatting in Vim by integrating existing code formatters.
- `F7` Autoformat
