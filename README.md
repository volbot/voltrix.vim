# VOLTRIX.vim
### `vim`/`nvim` Plugin for [VOLTRIX](https://gitlab.com/volbot/voltrix/)

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

## Usage

`voltrix` will begin using its colors for `vim`'s default highlight groups out of the box.

However, it is best used alongside syntax highlighting plugins.

### `vim`

For everyone's sake, I won't sit here and rehash syntax highlighting for `vim`. It's often subjective, and whatever I write will likely be superceded by entirely new plugins within the hour.

That being said, your two main options are:

 1. configuring an LSP, which is its own (much worthwhile) beast
 2. one-off syntax grouping plugins

I used a combination of these before switching to `nvim`. Option #1 can be cpu-time intensive, as `vim` does not run asynchronously, but Option #2 can sometimes over-highlight things. Use whichever you like best.

### `nvim`

`nvim` is far simpler. Your LSP will often highlight for you, but I find [`nvim-treesitter`](https://github.com/nvim-treesitter/nvim-treesitter) to do a far better job than any unconfigured LSP. 

Like with `vim`, this boils down to preference, but `nvim`'s proclivity for language processing allows for far better detail with far less intervention.

## Source

The source colortemplate and a few other distributions are available on [GitLab](https://gitlab.com/volbot/voltrix).
