# VSCode Modern v2 theme for Neovim, Dark & Light versions

![Example](example.png)

# Installation

[lazy.nvim](https://github.com/folke/lazy.nvim)
```lua
{
    "pvtrn/vscode.nvim",
    lazy = false,
    priority = 1000,
    config = function()
        require("vscode").setup({
            cursorline = true,
            transparent_background = true,
            nvim_tree_darker = true,
        })
        vim.cmd.colorscheme("vscode")
    end,
}
```
