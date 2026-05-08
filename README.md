# Neovim Config

A modern Neovim setup built with Lua and powered by Lazy.nvim.

## Features

- Fast startup with Lazy.nvim
- Clean Lua-based configuration
- Custom editor options and keymaps
- Modular plugin setup
- Minimal and distraction-free workflow

## Preview

![Screenshot](https://res.cloudinary.com/dlkweskt1/image/upload/v1778221895/Screenshot_From_2026-05-06_11-50-37_lihyvi.png)

## Structure

```text
.
├── init.lua
├── lazy-lock.json
└── lua
    ├── options.lua
    └── plugins.lua
```

## Installation

Clone the repository:

```bash
git clone https://github.com/devsterxyz/nvim ~/.config/nvim
```

Start Neovim:

```bash
nvim
```

Lazy.nvim will automatically install plugins on first launch.

## Goals

- Keep the configuration simple and readable
- Learn the Neovim ecosystem
- Build a productive development environment
