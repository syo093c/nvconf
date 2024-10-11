NvChad places all library code in a package, which is installed by `lazy` at the path:
`~/.local/share/nvim/lazy/NvChad`

Therefore, the code in this package cannot be modified directly. We can only make changes through the configuration files.

Current structure of NvChad:
```
├── LICENSE
├── README.md
└── lua
    └── nvchad
        ├── autocmds.lua
        ├── configs
        │   ├── cmp.lua
        │   ├── gitsigns.lua
        │   ├── lspconfig.lua
        │   ├── luasnip.lua
        │   ├── mason.lua
        │   ├── nvimtree.lua
        │   ├── telescope.lua
        │   └── treesitter.lua
        ├── mappings.lua
        ├── options.lua
        └── plugins
            └── init.lua
```
When making changes, modify the corresponding configuration files.

