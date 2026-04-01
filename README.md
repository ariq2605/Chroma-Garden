Chroma Garden is a specialized Python-based tool designed for developers and designers who need a fast, "brutalist" interface for managing color palettes. It focuses on practical functionality, allowing you to pick, save, and organize HEX codes into local databases.

Key Features:
Pixel-Perfect Selection: Includes a magnification tool to grab exact colors from any part of your screen.

Palette Generation: Automatically suggests matching color schemes based on your primary selection.

SQLite Storage: Saves your custom palettes to a local database for persistent access across sessions.

High-Contrast UI: Designed with a neon-purple and black aesthetic to match a "Wired" or brutalist desktop environment.

How to Use on Linux
Since you are running CachyOS with Hyprland, you can integrate Chroma Garden directly into your workflow using the terminal.

1. Prerequisites
Ensure you have Python and the necessary development headers installed:

Bash
sudo pacman -S python python-pip python-gobject
2. Installation
Clone the repository and install the required dependencies:

Bash
git clone https://github.com/ariq2605/chroma-garden
cd chroma-garden
pip install -r requirements.txt
3. Running the App
You can launch the utility directly from your terminal:

Bash
python main.py
4. Pro-Tip: Hyprland Bind
To make it feel like a native part of your "ricing" setup, add a keybind to your hyprland.conf to launch it instantly:

Code snippet
bind = $mainMod, C, exec, python ~/path/to/chroma-garden/main.py
