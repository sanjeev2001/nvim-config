# Dev Environment

## nvim
#### Installation
```
mkdir ~/.config/nvim
git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1
git clone https://github.com/sanjeev2001/nvim-config.github
cp -r nvim-config/lua/custom/ ~/.config/nvim/lua/
```
#### Plugins
- neovim/nvim-lspconfig
- williamboman/mason.nvim
    - Ensure Installed:
        - black
        - debugpy
        - mypy
        - ruff
        - pyright
- nvimtools/none-ls.nvim
    - nvimtools/none-ls-extras.nvim
- mfussenegger/nvim-dap-python
    - mfussenegger/nvim-dap
    - rcarriga/nvim-dap-ui
    - nvim-neotest/nvim-nio
- mfussenegger/nvim-dap
- rcarriga/nvim-dap-ui
    - mfussenegger/nvim-dap
- nvim-neotest/nvim-nio 
- christoomey/vim-tmux-navigator 
- github/copilot.vim
- iamcco/markdown-preview.nvim
