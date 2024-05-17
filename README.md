## Vez's nvim config

Except not really. All of it was made following ThePrimeagen's tutorial.

## Installation
- Install packer.nvim

  On Linux distros:
  ```
  git clone --depth 1 https://github.com/wbthomason/packer.nvim\
  ~/.local/share/nvim/site/pack/packer/start/packer.nvim
  ```

  On Windows:
  ```
  git clone https://github.com/wbthomason/packer.nvim "%LOCALAPPDATA%\nvim-data\site\pack\packer\start\packer.nvim"
  ```
- Clone the config file
  On Linux:
  ```
  git clone https://github.com/vdsbt33/nvim-config.git ~/.config/nvim
  ```
  On Windows:
  ```
  git clone https://github.com/vdsbt33/nvim-config.git "%LOCALAPPDATA%\nvim"
  ```

- Install the packages

  Run `:PackerSync` on neovim. This will install all packages.
  If you are on Windows, you will need to install a C Compiler (such as GCC or MinGW) before you can do that.

- [Optional] Install ripgrep. It makes telescope.nvim respect .gitignore when inside Git folders.
It's especially useful when there's a node_modules folder neaby.
