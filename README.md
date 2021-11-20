# nvim-miek
My configuration for neovim.  

It is based heavily on the good work of [tjdevries](https://github.com/tjdevries) and
 [mljback](https://github.com/mjlbach) - follow them and read their work. Your workflow will improve, and you'll learn good things.

## Installation
  - Backup your configuration
  - Save `init.lua` into `$HOME/.config/nvim/init.lua`
  - Start `nvim`
  - Run `:PackerInstall` and ignore startup warning
  - Quit and restart `nvim`

## Dependencies
I use the following in my neovim editor
### Language Servers
[LSP](https://langserver.org) requires both server and client support in your environment.
Clients are installed in init.lua with a package manager like [packer.nvim](https://github.com/wbthomason/packer.nvim),
and servers must be installed on your machine and be available in your PATH.

I use the following servers
  - [bash](https://github.com/bash-lsp/bash-language-server)
  - [clangd](https://clangd.llvm.org/installation)
  - [Haskell](https://haskell-language-server.readthedocs.io/en/latest/)
  - [Python](https://github.com/python-lsp/python-lsp-server)
  - [Verilog](https://github.com/dalance/svls/releases/tag/v0.1.28)

