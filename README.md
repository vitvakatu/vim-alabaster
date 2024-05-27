# Alabaster colorscheme

My personal Vim (Neovim) colorscheme. Based on [Tonsky’s colorscheme](https://github.com/tonsky/sublime-scheme-alabaster).

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
