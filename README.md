# lsp_lines.nvim

`lsp_lines` is a simple neovim plugin that renders diagnostics using virtual
lines on top of the real line of code.

# Installation

```lua
  "9th8/lsp_lines.nvim",
```

# Configuration

This plugin's functionality can be disabled with:

```lua
vim.diagnostic.config({ virtual_lines = false })
```

And it can be re-enabled via:

```lua
vim.diagnostic.config({ virtual_lines = true })
```

The prefix icon shown to the left of diagnostics can be configured with:

```lua
vim.diagnostic.config({ virtual_lines = { prefix = "🔥" } })
