# Neovim Keybindings Cheatsheet

> `<leader>` = Space

## Basic

| Key | Mode | Description |
|-----|------|-------------|
| `;;` | Insert | Exit insert mode |
| `Ctrl+s` | Normal / Visual / Insert | Save file |
| `Ctrl+/` | Normal / Visual / Insert | Toggle comment |
| `Esc` | Normal | Clear search highlight |
| `Esc Esc` | Terminal | Exit terminal mode |

## Window Navigation

| Key | Description |
|-----|-------------|
| `Ctrl+h` | Move focus to left window |
| `Ctrl+j` | Move focus to lower window |
| `Ctrl+k` | Move focus to upper window |
| `Ctrl+l` | Move focus to right window |

## Tab Management

| Key | Description |
|-----|-------------|
| `<leader>tn` | New tab |
| `<leader>tc` | Close tab |
| `<leader>tt` | Next tab |
| `<leader>tp` | Previous tab |
| `<leader>to` | Close all other tabs |
| `<leader>t1` ~ `t5` | Go to tab 1 ~ 5 |

## Telescope Search

| Key | Description |
|-----|-------------|
| `<leader>sf` | Search files by name |
| `<leader>sg` | Live grep (search text across all files) |
| `<leader>sw` | Search word under cursor |
| `<leader>sk` | Search keymaps |
| `<leader>sh` | Search help tags |
| `<leader>ss` | Search Telescope builtins |
| `<leader>sd` | Search diagnostics |
| `<leader>sr` | Resume last search |
| `<leader>s.` | Search recent files |
| `<leader>sn` | Search Neovim config files |
| `<leader>/` | Fuzzy search in current buffer |
| `<leader>s/` | Live grep in open files only |
| `<leader><leader>` | Switch between open buffers |

## LSP (Language Server Protocol)

| Key | Description |
|-----|-------------|
| `grn` | Rename symbol under cursor |
| `gra` | Code action (Normal / Visual) |
| `grr` | Go to references |
| `gri` | Go to implementation |
| `grd` | Go to definition |
| `grD` | Go to declaration |
| `grt` | Go to type definition |
| `gO` | Document symbols (functions, variables, etc.) |
| `gW` | Workspace symbols (search across project) |

## Git - Fugitive

| Key | Description |
|-----|-------------|
| `<leader>gg` | Git status (fugitive) |
| `<leader>gd` | Git diff |

## Git - LazyGit

| Key | Description |
|-----|-------------|
| `<leader>lg` | Open LazyGit |
| `<leader>lG` | LazyGit current file |
| `<leader>lC` | LazyGit config |
| `<leader>lF` | LazyGit filter |
| `<leader>lf` | LazyGit filter current file |

## Git - Gitsigns (Hunk Operations)

| Key | Mode | Description |
|-----|------|-------------|
| `]c` | Normal | Jump to next git change |
| `[c` | Normal | Jump to previous git change |
| `<leader>hs` | Normal / Visual | Stage hunk |
| `<leader>hr` | Normal / Visual | Reset hunk |
| `<leader>hS` | Normal | Stage entire buffer |
| `<leader>hu` | Normal | Undo stage hunk |
| `<leader>hR` | Normal | Reset entire buffer |
| `<leader>hp` | Normal | Preview hunk |
| `<leader>hb` | Normal | Blame line |
| `<leader>hd` | Normal | Diff against index |
| `<leader>hD` | Normal | Diff against last commit |
| `<leader>tb` | Normal | Toggle inline git blame |
| `<leader>tD` | Normal | Toggle show deleted |

## Oil.nvim (File Explorer)

| Key | Description |
|-----|-------------|
| `<leader>o` | Open Oil in floating window |

### Inside Oil Buffer

| Key | Description |
|-----|-------------|
| `g?` | Show help |
| `Enter` | Open file / directory |
| `Ctrl+v` | Open in vertical split |
| `Ctrl+t` | Open in new tab |
| `Ctrl+p` | Preview |
| `q` / `Ctrl+c` | Close Oil |
| `Ctrl+l` | Refresh |
| `-` | Go to parent directory |
| `_` | Open cwd |
| `` ` `` | Change directory |
| `~` | Change tab directory |
| `gs` | Change sort |
| `gx` | Open external |
| `g.` | Toggle hidden files |
| `g\` | Toggle trash |

## Terminal

| Key | Description |
|-----|-------------|
| `<leader>tr` | Toggle terminal (right side) |
| `<leader>ti` | Toggle terminal (bottom) |
| `<leader>st` | Toggle terminal |

## Diagnostics

| Key | Description |
|-----|-------------|
| `<leader>q` | Open diagnostic quickfix list |
