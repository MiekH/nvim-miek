# nvim-miek
My configuration for [neovim](https://github.com/neovim/neovim).  I generally run off nightly builds.


## Installation
  - Backup your configuration
  - Save `init.lua` into `$HOME/.config/nvim/init.lua`
  - Start `nvim`
  - Run `:PackerInstall` and ignore startup warning
  - Quit and restart `nvim`

## Primary Dependencies
I use the following in my neovim editor. Many of these come with their own dependencies; see respective `Install` comments.
  - [packer.nvim](https://github.com/wbthomason/packer.nvim) (package manager)
  - [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) (fuzzy find)
  - [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)  (auto-completer)
  - [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) (highlighting/syntax)
  - [nvim-tree](https://github.com/kyazdani42/nvim-tree.lua) (sidebar file explorer)
  - [neovim LSP]( https://neovim.io/doc/user/lsp.html) (languages support)

### Language Servers
Special note: [LSP](https://langserver.org) requires both server and client support in your 
environment for each [language](https://microsoft.github.io/language-server-protocol/implementors/servers/) you want to involve.
Clients are setup in `init.lua` and executable servers must be installed on your machine and be available in your PATH.

I use the following servers
  - [bash](https://github.com/bash-lsp/bash-language-server)
  - [clangd](https://clangd.llvm.org/installation)
  - [Haskell](https://haskell-language-server.readthedocs.io/en/latest/)
  - [Python](https://github.com/python-lsp/python-lsp-server)
  - [Verilog](https://github.com/dalance/svls/releases/tag/v0.1.28)

