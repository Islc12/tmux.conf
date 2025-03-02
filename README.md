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
| Split window horizontally  | `Ctrl-b %`          |
| Split window vertically    | `Ctrl-b "`          |
| Switch panes               | `Ctrl-b (Arrow keys)` |
| Resize panes               | `Ctrl-b (Hold Alt + Arrow keys)` |
| Create new window          | `Ctrl-b c`          |
| Switch windows             | `Ctrl-b n / p`      |
| Kill current pane          | `Ctrl-b x`          |
| Reload tmux config         | `Ctrl-b r`          |

## Dependencies
- `tmux` (>= 3.0 recommended)
- `xclip` or `xsel` (for clipboard integration on Linux)
- `reattach-to-user-namespace` (for macOS clipboard support)

## Customization
Feel free to modify `.tmux.conf` to fit your workflow. To apply changes, reload the configuration using:
```bash
tmux source-file ~/.tmux.conf
```
