# Neovim Custom Keybindings Manual

This document provides a reference for the custom keybindings configured in Neovim.

## General Settings

### Leader Key
- Sets the **leader key** to **space (`<leader>`)**.
- The leader key is used as a prefix for many shortcuts.

---

## Navigation and File Explorer

### Open File Explorer (Netrw)
- **`<leader>pv`** → Opens the built-in file explorer (Netrw).

### Better Scrolling
- **`Ctrl + d` / `Ctrl + u`** → Scrolls half a page **while centering the cursor**.

### Improved Search Navigation
- **`n` / `N`** → Jumps to the next/previous search result and centers the screen.

---

## Editing Enhancements

### Move Selected Lines in Visual Mode
- **`J` in Visual Mode** → Moves selected text **down**.
- **`K` in Visual Mode** → Moves selected text **up**.

### Better Joining of Lines
- **`J`** → Joins the next line with the current line while preserving the cursor position.

### Improved Paste in Visual Mode
- **`<leader>p` in Visual Mode** → Pastes without overwriting the unnamed register.

---

## Clipboard and Deleting

### Copy to System Clipboard
- **`<leader>y`** → Copy to the **system clipboard**.
- **`<leader>Y`** → Copy an **entire line** to the system clipboard.

### Delete Without Copying
- **`<leader>d`** → Deletes to the black hole register (does not copy).

---

## LSP & Formatting

### Format Code with LSP
- **`<leader>f`** → Formats the current file using **LSP formatting**.

### Smart Replace for the Current Word
- **`<leader>s`** → Starts a **global find & replace** for the **word under the cursor**.

---

## Miscellaneous

### Disable `Q` (Legacy Command Mode)
- **Disables accidental `Q`** (which enters Ex mode).

### Make File Executable
- **`<leader>x`** → Makes the **current file executable**.

### Quick Open Neovim Config
- **`<leader>vpp`** → Opens the Neovim plugin configuration file.

### Reload Neovim Config
- **`<leader><leader>` (Double leader key)** → Reloads the Neovim configuration (`source` config).

---

## Quickfix & Location List Navigation
- **`Ctrl + k / Ctrl + j`** → Moves up/down through the **Quickfix list**.
- **`<leader>k / <leader>j`** → Moves up/down through the **Location List**.
