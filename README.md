# Default+

A dark color theme for Neovim, originally created as an Xcode Font & Color Theme.

Part of the [Default+ theme family](https://github.com/otaviocc/default-plus).

## Installation

### lazy.nvim

```lua
{
    "otaviocc/default-plus-nvim",
    lazy = false,
    priority = 1000,
    config = function()
        vim.cmd("colorscheme default-plus")
    end,
}
```

### vim-plug

```vim
Plug 'otaviocc/default-plus-nvim'
colorscheme default-plus
```

### packer.nvim

```lua
use {
    "otaviocc/default-plus-nvim",
    config = function()
        vim.cmd("colorscheme default-plus")
    end,
}
```

## Requirements

Neovim with `termguicolors` enabled (set automatically by the theme).
