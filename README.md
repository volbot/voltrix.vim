# VOLTRIX.vim
### Vim/Neovim Plugin for [VOLTRIX](https://gitlab.com/volbot/voltrix/)

&emsp; **「VOLTRIX」** is a sweet, maximalist colorscheme that invokes the whimsical uniformity of pastels, without sacrificing the placating vibrance of postmodernity.

&emsp; This is a `vim`/`nvim` plugin, installable via your favorite plugin manager.


## Installation

### via plugin manager

`VOLTRIX.vim` should be installable by any `git`-based plugin manager. Here are a few examples:

<details><summary>

#### [vim-plug](https://github.com/junegunn/vim-plug)

</summary><br>

```vim
call plug#begin()
Plug 'volbot/voltrix.vim'
call plug#end()
```

Then, either in the `vim` command prompt or in `vimrc`:

```vim
colorscheme voltrix
```

</details>

<details><summary>

#### [lazy.nvim](https://github.com/folke/lazy.nvim?tab=readme-ov-file#-structuring-your-plugins)

</summary><br>

Add `voltrix.vim` to your `lazy.nvim` setup, like so:

```lua
require("lazy").setup({
    { "volbot/voltrix.vim" },
})
```

At this point, a regular `:colorscheme` command will activate `voltrix`, but most `lazy.nvim` setups involve some smart colorscheme-loader, so simply load as you would any other built-in colorscheme.

</details>

### manually

Simply download `voltrix.vim` from the downloads page, put it in your relevant `colors` directory, and enable.

**vim:** `$HOME/.vim/colors/voltrix.vim`
**nvim:** `$CONFIG_HOME/nvim/colors/voltrix.vim`

## Source

The source colortemplate and a few other distributions are available on [GitLab](https://gitlab.com/volbot/voltrix).
