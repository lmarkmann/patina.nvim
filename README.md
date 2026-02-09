# patina.nvim

A warm, muted dark colorscheme for Neovim with earthy greens, aged copper tones, and soft contrast. Designed for long coding sessions.

## Features

- Treesitter support
- LSP semantic token support
- LSP diagnostics
- Plugin support: Telescope, nvim-cmp, nvim-tree, gitsigns, indent-blankline, which-key, lazy.nvim

## Installation

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "lmarkmann/patina.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("patina-dark")
  end,
}
```

### [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use {
  "lmarkmann/patina.nvim",
  config = function()
    vim.cmd.colorscheme("patina-dark")
  end,
}
```

## Palette

| Role       | Hex       |
|------------|-----------|
| Background | `#121212` |
| Foreground | `#dbd7ca` |
| Comment    | `#758575` |
| Keyword    | `#4d9375` |
| String     | `#c98a7d` |
| Function   | `#80a665` |
| Type       | `#5da9a7` |
| Variable   | `#bd976a` |
| Control    | `#cb7676` |
| Number     | `#4c9a91` |

## License

MIT
