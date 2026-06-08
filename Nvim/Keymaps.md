# Nvim Keymaps

## Completion Suggestions

Your Neovim setup uses LazyVim with `blink.cmp` for completion.

| Key | Action |
| --- | --- |
| `Ctrl-n` | Move to the next suggestion |
| `Ctrl-p` | Move to the previous suggestion |
| `Down` | Move to the next suggestion |
| `Up` | Move to the previous suggestion |
| `Enter` | Accept the currently selected suggestion |
| `Ctrl-y` | Select and accept a suggestion, even if nothing is selected |
| `Ctrl-e` | Cancel or close the suggestions menu |
| `Ctrl-Space` | Manually open suggestions or documentation |
| `Ctrl-f` | Scroll documentation down |
| `Ctrl-b` | Scroll documentation up |

## Command-Line Mode

When using command-line mode, such as after pressing `:`, these also apply:

| Key | Action |
| --- | --- |
| `Tab` | Cycle to the next suggestion |
| `Shift-Tab` | Cycle to the previous suggestion |

## Notes

- In insert mode, `Tab` is mainly used for snippets or AI acceptance fallback in this setup.
- For regular completion navigation in insert mode, prefer `Ctrl-n` and `Ctrl-p`.

