# Example_config

This can be used as an example custom config for NvChad. Do check the https://github.com/NvChad/nvcommunity

Tech Stack : MERN

# Neovim Tips and Tricks

This document provides a well-organized list of Neovim tips and tricks for efficient coding. The tips cover various commands and shortcuts that can enhance your productivity.

## Table of Contents

1. [Selecting Text](#selecting-text)
2. [Navigation](#navigation)
3. [File Operations](#file-operations)
4. [Editing and Deleting](#editing-and-deleting)
5. [Undo and Redo](#undo-and-redo)
6. [Copying and Pasting](#copying-and-pasting)
7. [Search and Replace](#search-and-replace)
8. [Tabs and Buffers](#tabs-and-buffers)
9. [Splits](#splits)

## Selecting Text

- `V`: Select the entire line.
- `va"`: Select text inside double quotes, including the quotes.
- `vi"`: Select text inside double quotes, excluding the quotes.
- `va{`: Select everything inside a paragraph, including parentheses.
- `vi{`: Select everything inside a paragraph, excluding parentheses.
- `vip`: Select a paragraph.
- `viW`: Select text using `j`, `k`, `l`, `h`.
- `viw`: Select the whole word.

## Navigation

- `ctrl+d`: Scroll down the page.
- `ctrl+u`: Scroll up the page.
- `shift [ or shift ]`: Vertically jump through paragraphs.
- `gd`: Go to the definition of code.
- `gt`: Switch between tabs.
- `gT`: Switch to the previous tab.

## File Operations

- `:{range}`: Move to a specific line.
- `wa`: Write and exit from Neovim.
- `q!`: Exit without saving changes.
- `Ctrl+g`: See file location and its status.

## Editing and Deleting

- `x`: Remove the character at the cursor.
- `dw`: Delete the word until the next word, excluding the next word's first character.
- `de`: Delete to the end of the word, including the last character.
- `d$`: Delete to the end of the line, including the last character.
- `dd`: Delete a line.
- `u`: Undo the last command.
- `U`: Return a line to its original state.

## Copying and Pasting

- `yy`: Copy a line.
- `p`: Paste before the cursor.
- `P`: Paste after the cursor.

## Search and Replace

- `/`: Search for a phrase.
- `n`: Move forward in search results.
- `N`: Move backward in search results.
- `:noh`: Remove search highlights.
- `:s/old/new/`: Substitute one character in a line.
- `:s/old/new/g`: Substitute all matching characters in a line.
- `:%s/old/new/g`: Substitute all matching characters in the whole file.
- `:%s/old/new/gc`: Substitute all matching characters in the whole file with a prompt.

## Tabs and Buffers

- `:tabnew`: Create a new tab.
- `gt`: Move to the next tab.
- `gT`: Move to the previous tab.
- `:sp`: Horizontal split.
- `:vsp`: Vertical split.

These tips cover a wide range of Neovim functionalities, helping you navigate and edit code more efficiently. Integrate these shortcuts into your workflow for a smoother coding experience.

