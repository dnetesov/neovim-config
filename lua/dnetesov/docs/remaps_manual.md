# Neovim Custom Keybindings Manual

This document provides a reference for all custom keybindings configured in Neovim.

---

## General Settings

### Leader Key
- **Leader key:** `Space`
- Used as a prefix for many shortcuts.

---

## Navigation and File Explorer
- **`<leader>pv`** → Open the **file explorer (Netrw)**.
- **`Ctrl + d / Ctrl + u`** → Scroll half a page **while centering the cursor**.
- **`n / N`** → Move to the **next/previous** search result and center the screen.

---

## Editing Enhancements
- **`J` (Visual Mode)** → Move **selected text down**.
- **`K` (Visual Mode)** → Move **selected text up**.
- **`J` (Normal Mode)** → Join lines while **preserving cursor position**.
- **`<leader>p`** (Visual Mode) → Paste without **overwriting the unnamed register**.

---

## Clipboard and Deleting
- **`<leader>y`** → Copy to the **system clipboard**.
- **`<leader>Y`** → Copy an **entire line** to the clipboard.
- **`<leader>d`** → Delete text **without copying** it.

---

## LSP & Formatting
- **`gd`** → Go to **definition**.
- **`K`** → Show **hover documentation**.
- **`<leader>vws`** → Search **workspace symbols**.
- **`<leader>vd`** → Open **diagnostics** in a floating window.
- **`<leader>vca`** → Perform **code actions**.
- **`<leader>vrr`** → Find **references**.
- **`<leader>vrn`** → **Rename** symbol.
- **`<C-h>`** → Show **signature help**.
- **`[d / ]d`** → Jump to **previous/next** diagnostic.
- **`<leader>f`** → Format file using **LSP formatting**.

---

## Quickfix & Location List Navigation
- **`Ctrl + k / Ctrl + j`** → Move up/down **Quickfix list**.
- **`<leader>k / <leader>j`** → Move up/down **Location List**.

---

## Find & Replace
- **`<leader>s`** → Replace **word under cursor** globally.

---

## File & Execution Commands
- **`<leader>x`** → Make file **executable** (`chmod +x`).
- **`<leader>vpp`** → Open **Neovim plugin config**.
- **`<leader><leader>`** → **Reload Neovim config**.

---

## Zen Mode
- **`<leader>zz`** → Toggle **Zen Mode**.
- **`<leader>zZ`** → Toggle **Zen Mode (wide screen)**.

---

## Snippets
- **`Ctrl + s e`** → Expand snippet.
- **`Ctrl + s ; / Ctrl + s ,`** → Jump forward/backward inside snippet.

---

## Telescope (Fuzzy Finder)
- **`<leader>pf`** → Find files.
- **`Ctrl + p`** → Find Git-tracked files.
- **`<leader>pws`** → Search for **word under cursor** in workspace.
- **`<leader>pWs`** → Search for word **everywhere**.
- **`<leader>ps`** → Open **search prompt**.
- **`<leader>vh`** → Open **help tags**.

---

## Trouble (Diagnostics List)
- **`<leader>tt`** → Toggle **Trouble**.
- **`[t / ]t`** → Jump to **previous/next issue**.

---

## Git Commands (Fugitive)
- **`<leader>gs`** → Open **Git status**.
- **`<leader>p`** → Git push.
- **`<leader>P`** → Git pull.
- **`<leader>t`** → Push to upstream branch.
- **`gu / gh`** → Select left/right diff during merge conflicts.

---

## Testing (Neotest)
- **`<leader>tc`** → Run **current test case**.
- **`<leader>tf`** → Run **test file**.

---

## Undo Tree
- **`<leader>u`** → Toggle **Undo Tree**.

---
