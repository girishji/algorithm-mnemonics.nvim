# Algorithm Mnemonics

C++ STL algorithm snippets suitable for NeoVim's Lua plugins, based on Tommy Bennet's snippets.

You can read this [excellent explanation](https://github.com/tommybennett/algorithm-mnemonics) with [video](https://www.youtube.com/watch?v=uzc2OWVZPnM). His [talk](https://youtu.be/tSq7yDwS1vM) at CppCon.

These snippets conform to LSP format, mostly sourced from David Brötje's [VScode extension](https://marketplace.visualstudio.com/items?itemName=davidbroetje.algorithm-mnemonics-vscode).
 
### Usage 

This collection of snippets should work with any plugin that supports loading
vscode snippets. Like for example:

- [LuaSnip](https://github.com/L3MON4D3/LuaSnip)
- [vim-vsnip](https://github.com/hrsh7th/vim-vsnip)
- [coc-snippets](https://github.com/neoclide/coc-snippets)

### Install

Use your plugin manager of choice, e.g.

```lua
-- Packer
use "girishji/algorithm-mnemonics.nvim"

-- Plug
Plug 'girishji/algorithm-mnemonics.nvim'

-- If you're using coc.nvim, you can use:
CocInstall https://github.com/girishji/algorithm-mnemonics.nvim@main
```

