Author: Richard Smith

Date: December 2024

Contact: richrsmith@proton.me

# tmux.conf

This repository contains my custom `tmux` configuration file, designed to enhance productivity and streamline terminal multiplexing.

## Features
- **Custom Keybindings** – Improved navigation and window management.
- **Status Bar Enhancements** – Clean and informative status line.
- **Mouse Support** – Seamless mouse interaction for pane resizing and window switching.
- **Clipboard Integration** – Simplified copy-pasting between `tmux` and system clipboard.
- **Vim-Friendly Navigation** – Consistent keybindings for Vim users.
- **Optimized Performance** – Efficient settings to reduce lag and improve responsiveness.

## Installation
1. Clone the repository or download `tmux.conf`:
   ```bash
   git clone https://github.com/Islc12/tmux.conf.git
   ```
2. Move the configuration file to your home directory:
   ```bash
   mv tmux.conf/.tmux.conf ~/.tmux.conf
   ```
3. Reload `tmux` configuration:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

## Keybindings
| Action                     | Keybinding           |
|----------------------------|----------------------|
| Split window horizontally  | `Ctrl-j/f %`          |
| Split window vertically    | `Ctrl-j/f "`          |
| Switch panes               | `Alt (Arrow keys)` |
| Create new window          | `Ctrl-j/f c`          |
| Switch windows             | `Ctrl-j/f n/p`      |
| Kill current pane          | `Ctrl-j/f x`          |
| Reload tmux config         | `Ctrl-j/f r`          |

## Dependencies
- `tmux` (>= 3.0 recommended)
- `xclip` or `xsel` (for clipboard integration on Linux)

## Customization
Feel free to modify `.tmux.conf` to fit your workflow. To apply changes, reload the configuration using:
```bash
tmux source-file ~/.tmux.conf
```
