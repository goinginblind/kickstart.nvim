# kickstart.nvim

## Introduction

* Basically a Kickstart Neovim setup (see [nvim-lua/kickstart.nvim][https://github.com/nvim-lua/kickstart.nvim])
* My own tweaks include:
    - Fix to the LSP config parsing (it parsed the LSP themselves, but not their configuration in the original)
    - LSPs configured for (besides default Lua one): 
        - Rust (both rust-analyzer and clippy)
        - Go (gopls, goimports on save, staticcheck)
        - Python (ruff and pyright)
    - Minor visual stuff like catpuccin theme, some style changes
    - And that's it!

