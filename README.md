# A brutalist color utility for the digital void.

Chroma Garden is a Python-based desktop tool designed for rapid color palette generation and management. Built with a high-contrast aesthetic, it functions as a lightweight companion for developers and designers who need to maintain visual consistency across their projects.

# Running from Source

Requirements

- Python 3.10+

- Pillow

- pyperclip

Install dependencies:

``pip install Pillow pyperclip``

# Linux Extra Steps

On Linux, additional configuration may be required for UI rendering and input capture.

1. Install tkinter (it is not always bundled with Python on Linux):

`# Arch / CachyOS
sudo pacman -S tk`

`# Debian / Ubuntu
sudo apt install python3-tk`

`# Fedora
sudo dnf install python3-tkinter`

# 2. Wayland Compatibility:
If you are using a Wayland compositor like Hyprland, you may need to set the environment variable to ensure the picker captures coordinates correctly:

``GDK_BACKEND=x11 python main.py``

# Run

``python main.py``

# Windows

Just run the ``.exe`` — no setup needed.
