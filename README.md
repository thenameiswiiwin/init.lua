# Neovim Key Mappings

This document provides a comprehensive reference for all the custom key mappings in this Neovim configuration.

## Table of Contents

- [General Navigation](#general-navigation)
- [File Navigation](#file-navigation)
- [Text Manipulation](#text-manipulation)
- [Clipboard Operations](#clipboard-operations)
- [Search and Replace](#search-and-replace)
- [Git Integration (fugitive)](#git-integration-fugitive)
- [Project Navigation (harpoon)](#project-navigation-harpoon)
- [Code Completion](#code-completion)
- [Debugging](#debugging)
- [Testing (neotest)](#testing-neotest)
- [Snippets](#snippets)
- [Telescope](#telescope)
- [Code Navigation and Diagnostics](#code-navigation-and-diagnostics)
- [Other Tools](#other-tools)

## General Navigation

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>pv` | `vim.cmd.Ex` | Open file explorer |
| Normal | `<C-d>` | `<C-d>zz` | Scroll down half a page and center cursor |
| Normal | `<C-u>` | `<C-u>zz` | Scroll up half a page and center cursor |
| Normal | `n` | `nzzzv` | Go to next search result and center cursor |
| Normal | `N` | `Nzzzv` | Go to previous search result and center cursor |
| Normal | `Q` | `<nop>` | Disable Ex mode (Q) |

## File Navigation

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<C-f>` | Open tmux-sessionizer | Open a new tmux window with tmux-sessionizer |
| Normal | `<leader><leader>` | Source current file | Reload the current configuration file |

## Text Manipulation

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Visual | `J` | Move selection down | Move selected lines down one line |
| Visual | `K` | Move selection up | Move selected lines up one line |
| Normal | `J` | `mzJ`z` | Join lines and keep cursor position |
| Normal | `=ap` | `ma=ap'a` | Format a paragraph and keep cursor position |
| Normal | `<leader>f` | Format buffer | Format the current buffer using conform |
| Insert | `<C-c>` | `<Esc>` | Exit insert mode with Ctrl+C |
| Normal | `<leader>x` | `chmod +x %` | Make the current file executable |

## Clipboard Operations

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Visual | `<leader>p` | `"_dP` | Paste over selection without yanking |
| Normal, Visual | `<leader>y` | `"+y` | Yank to system clipboard |
| Normal | `<leader>Y` | `"+Y` | Yank line to system clipboard |
| Normal, Visual | `<leader>d` | `"_d` | Delete without yanking |

## Search and Replace

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>s` | `:%s/\<<C-r><C-w>\>/<C-r><C-w>/gI<Left><Left><Left>` | Search and replace current word |

## Git Integration (fugitive)

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>gs` | Open Git status | Open Git status window |
| Normal (fugitive) | `<leader>p` | Git push | Push changes to remote |
| Normal (fugitive) | `<leader>P` | Git pull rebase | Pull changes with rebase |
| Normal (fugitive) | `<leader>t` | Custom push | Push with tracking setup |
| Normal | `gu` | `<cmd>diffget //2<CR>` | Get diff from left side |
| Normal | `gh` | `<cmd>diffget //3<CR>` | Get diff from right side |

## Project Navigation (harpoon)

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>A` | Prepend to harpoon list | Add current file to beginning of harpoon list |
| Normal | `<leader>a` | Add to harpoon list | Add current file to harpoon list |
| Normal | `<C-e>` | Toggle harpoon menu | Open/close the harpoon quick menu |
| Normal | `<C-h>` | Jump to file 1 | Jump to first marked file |
| Normal | `<C-t>` | Jump to file 2 | Jump to second marked file |
| Normal | `<C-n>` | Jump to file 3 | Jump to third marked file |
| Normal | `<C-s>` | Jump to file 4 | Jump to fourth marked file |
| Normal | `<leader><C-h>` | Replace file 1 | Replace first marked file with current file |
| Normal | `<leader><C-t>` | Replace file 2 | Replace second marked file with current file |
| Normal | `<leader><C-n>` | Replace file 3 | Replace third marked file with current file |
| Normal | `<leader><C-s>` | Replace file 4 | Replace fourth marked file with current file |

## Code Completion

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Insert | `<C-p>` | Select previous item | Navigate to previous completion item |
| Insert | `<C-n>` | Select next item | Navigate to next completion item |
| Insert | `<C-y>` | Confirm selection | Confirm current completion selection |
| Insert | `<C-Space>` | Complete | Show completion suggestions |

## Debugging

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>dr` | Toggle debug REPL | Toggle debug REPL UI |
| Normal | `<leader>ds` | Toggle debug stacks | Toggle debug stacks UI |
| Normal | `<leader>dw` | Toggle debug watches | Toggle debug watches UI |
| Normal | `<leader>db` | Toggle debug breakpoints | Toggle debug breakpoints UI |
| Normal | `<leader>dS` | Toggle debug scopes | Toggle debug scopes UI |
| Normal | `<leader>dc` | Toggle debug console | Toggle debug console UI |
| Normal | `<F8>` | Debug continue | Continue debugging |
| Normal | `<F10>` | Debug step over | Step over in debugger |
| Normal | `<F11>` | Debug step into | Step into in debugger |
| Normal | `<F12>` | Debug step out | Step out in debugger |
| Normal | `<leader>b` | Toggle breakpoint | Toggle breakpoint at current line |
| Normal | `<leader>B` | Set conditional breakpoint | Set conditional breakpoint |

## Testing (neotest)

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>tr` | Run nearest test | Run the nearest test |
| Normal | `<leader>tv` | Toggle test summary | Toggle test summary view |
| Normal | `<leader>ts` | Run test suite | Run the entire test suite |
| Normal | `<leader>td` | Debug nearest test | Debug the nearest test |
| Normal | `<leader>to` | Open test output | Open test output window |
| Normal | `<leader>ta` | Run all tests | Run all tests in current directory |

## Snippets

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Insert | `<C-s>e` | Expand snippet | Expand the current snippet |
| Insert, Select | `<C-s>;` | Jump forward | Jump to next snippet placeholder |
| Insert, Select | `<C-s>,` | Jump backward | Jump to previous snippet placeholder |
| Insert, Select | `<C-E>` | Change choice | Change the current choice in a snippet |

## Telescope

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>pf` | Find files | Find files in current directory |
| Normal | `<C-p>` | Git files | Find files tracked by Git |
| Normal | `<leader>pws` | Search current word | Search for occurrences of word under cursor |
| Normal | `<leader>pWs` | Search current WORD | Search for occurrences of WORD under cursor |
| Normal | `<leader>ps` | Grep | Search with grep prompt |
| Normal | `<leader>vh` | Help tags | Search through help tags |

## Code Navigation and Diagnostics

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>tf` | Run Plenary test file | Run the current test file with Plenary |
| Normal | `<leader>zig` | Restart LSP | Restart the Language Server |
| Normal | `<C-k>` | Next quickfix | Go to next item in quickfix list |
| Normal | `<C-j>` | Previous quickfix | Go to previous item in quickfix list |
| Normal | `<leader>k` | Next location | Go to next item in location list |
| Normal | `<leader>j` | Previous location | Go to previous item in location list |
| Normal | `<leader>tt` | Toggle trouble | Toggle trouble diagnostic viewer |
| Normal | `[t` | Next trouble item | Jump to next trouble item |
| Normal | `]t` | Previous trouble item | Jump to previous trouble item |

## Other Tools

| Mode | Mapping | Action | Description |
|------|---------|--------|-------------|
| Normal | `<leader>vwm` | Start Vim With Me | Start Vim With Me session |
| Normal | `<leader>svwm` | Stop Vim With Me | Stop Vim With Me session |
| Normal | `<leader>ee` | Go error handling | Insert Go error check pattern |
| Normal | `<leader>ea` | Go assert.NoError | Insert Go assert.NoError pattern |
| Normal | `<leader>ef` | Go log.Fatalf | Insert Go log.Fatalf pattern |
| Normal | `<leader>el` | Go logger.Error | Insert Go logger.Error pattern |
| Normal | `<leader>ca` | Run cellular automaton | Start "make it rain" animation |
| Normal | `<leader>u` | Toggle Undotree | Toggle the undo tree visualization |
| Normal | `<leader>zz` | Toggle Zen mode | Toggle Zen mode for focused writing |

## Commands

| Command | Action | Description |
|---------|--------|-------------|
| `PeekOpen` | Open Peek | Open the markdown preview |
| `PeekClose` | Close Peek | Close the markdown preview |
