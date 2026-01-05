# Alabaster colorscheme

My personal Vim (Neovim) colorscheme. Based on [Tonsky’s colorscheme](https://github.com/tonsky/sublime-scheme-alabaster).

## Editing

1. Install vim-colortemplate:
```
{
  "lifepillar/vim-colortemplate",
  branch = "v2",
  cmd = "Colortemplate",
  init = function()
    -- Neovim does not support topbar menu, so we disable it.
    vim.g.colortemplate_toolbar = 0
  end,
}
```
2. Open `./alabaster.colortemplate`
3. Do necessary edits.
4. `:set ft=colortemplate`
5. `:Colortemplate! .`

## Installation

Using `lazy.nvim`:

```
{
    "vitvakatu/vim-alabaster",
    lazy = false,
    priority = 1000,
    config = function()
        vim.cmd([[colorscheme alabaster]])
    end
}
```

## License

[MIT](./LICENSE)
