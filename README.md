Welcome.

1. Plugins
2. Key maps


1. Plugins used:

1) lazy. nvim - plugin manager - https://github.com/folke/lazy.nvim
2) nvim-tree.lua - file explorer - https://github.com/nvim-tree/nvim-tree.lua
3) nvim-web-devicons - icons for the file explorer - https://github.com/nvim-tree/nvim-web-devicons
4) ChatGPT.nvim - plugin for integrating ChatGPT - https://github.com/jackMort/ChatGPT.nvim
5) nui.nvim - UI library for neovim - https://github.com/MunifTanjim/nui.nvim
6) plenary.nvim - Lua utility functions for neovim plugins(async) - https://github.com/nvim-lua/plenary.nvim
7) telescope.nvim - highly customizable fzf plugin - https://github.com/nvim-telescope/telescope.nvim
8) vim-fugitive - git integration - https://github.com/tpope/vim-fugitive
9) vim-rhubarb - GitHub integration - https://github.com/tpope/vim-rhubarb
10) vim-sleuth - automatic detection of indent settings(not perfect, might require to reopen a file if created in nvim-tree but works pretty well overall) - https://github.com/tpope/vim-sleuth
11) nvim-lspconfing - configuration for nvim's built-in LSP - https://github.com/neovim/nvim-lspconfig
12) mason.nvim - tool for managing external tools used by LSPs - https://github.com/williamboman/mason.nvim
13) mason-lspconfig.nvim - integration of mason.nvim with nvim-lspconfig - https://github.com/williamboman/mason-lspconfig.nvim
14) fidget.nvim - status updates for LSP, little ui in corner - https://github.com/j-hui/fidget.nvim
15) neodev.nvim - language server for lua nvim config - https://github.com/folke/neodev.nvim
16) nvim-cmp - code completion engine written in lua - https://github.com/hrsh7th/nvim-cmp
17) cmp-nvim-lsp - LSP source for nvim-cmp, supports more types of completion canditates than built-in - https://github.com/hrsh7th/cmp-nvim-lsp
18) LuaSnip - snippet engine - https://github.com/L3MON4D3/LuaSnip
19) cmp_luasnip - integrates LuaSnip with nvim-cmp - https://github.com/saadparwaiz1/cmp_luasnip
20) vimspector - debugger integration - https://github.com/puremourning/vimspector
21) which-key.nvim - displaying keybinds, ez mode - https://github.com/folke/which-key.nvim
22) gitsigns.nvim - sings for changed/added/removed lines etc - https://github.com/lewis6991/gitsigns.nvim
23) onedark.nvim - theme inspired by atom - https://github.com/navarasu/onedark.nvim
24) lualine.nvim - pretty status line - https://github.com/nvim-lualine/lualine.nvim
25) indent-blankline.nvim - indentation lines -https://github.com/lukas-reineke/indent-blankline.nvim
26) comment.nvim - plugin for easy commenting of code - https://github.com/numToStr/Comment.nvim
27) telescope-fzf-native.nvim - fzf native integration for telescope - https://github.com/nvim-telescope/telescope-fzf-native.nvim
28) nvim-treesitter - syntax highlighting and code manipulation - https://github.com/nvim-treesitter/nvim-treesitter
29) nvim-treesitter-textobjects - better ways to select and manipulate different parts of code - https://github.com/nvim-treesitter/nvim-treesitter-textobjects
30) copilot.vim - copilot ... - https://github.com/github/copilot.vim
31) kickstart.plugins.autoformat - autoformat(commented out) - https://github.com/kickstart-app/kickstart-plugins
32) kickstart.plugins.debug - debugging(commented out) - https://github.com/kickstart-app/kickstart-plugins

I might have missed some, probably missed something, explenations are not very detailed but that's why the links are there, get to reading.


2. Key mpas

1) <F3> - normal mode - TOggles the nvim-tree(file explorer) window.
2) <F4> - normal mode - opens the copilot window for suggestions 10 suggestions
3) <Space>? - normal mode - list of recently opened files telescope
4) <Space><Space> - normal mode - opens telescope for existing buffers
5) <Space> / -  normal mode - opens current buffer fuzzy search
6) <Space>sf - normal mode - telescope files in current project
7) <Space> sh - normal mode - telescope to help search for help tags, it's pretty cool
8) <Space> sw - normal mode - telescope to look for current word in the project
9) <Space> sg - normal mode - telescope to look for word accorss project
10) <Space> sd - normal mode - telescope search for diagnostics
11) [d or ]d - normal mode - previous or next diagnostic message
12) <Space> e - normal mode - opens a floating diagnostic message
13) <space> q - normal mode - opens diagnostic list
14) ctrl l - insert mode - accepts only one word from copilot suggestion, there are currently 2 versions of the function SuggestOneWord(), one accepts a word until the first sign or space and won't accept the sign or space if it's the next word, the other one accepts the word plus the first sign or space, test both and decide for yourself.
15) gd - will search whatever word the cursor is on

Pretty sure there are more, will add them as I remember them, might go through the file at some point to look for them, I've made some mappings that don't seem to work but not super important so haven't played around to get them to work.

You are welcome.
