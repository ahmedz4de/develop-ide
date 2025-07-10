# Description

Develop-IDE is a fake IDE. It uses a custom layout and configuration for the Zellij Terminal Multiplexer to render two tabs: one opens the Micro Text Editor, and the other opens a terminal.

It does not support any features except those provided by `zellij` and `micro`.

# Installation

1. Make sure you have `zellij`, `micro` and `bash` installed.
2. Download `develop.sh`
3. Make it executable: `sudo chmod +x develop.sh`
4. Make it runnable from anywhere: `sudo mv develop.sh /usr/local/bin/develop`

# Usage

Simply call `develop` with file names specified (multiple files supported).
<pre> $ develop yourfile1.txt yourfile2.txt </pre>

Bu default, `zellij` will be launched in locked mode to not interfere with `micro`'s keybinding.

To exit `develop`:
1. Press Ctrl + G to exit locked mode
2. Then press Ctrl + Q to close the app

<img width="1070" height="1146" alt="Screenshot From 2025-07-10 15-13-14" src="https://github.com/user-attachments/assets/171b698c-46fd-43e2-acbb-97e06605a146" />
