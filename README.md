# 🐧 HyprGnome

<p align="center">
  <img src="https://img.shields.io" />
  <img src="https://img.shields.io" />
  <img src="https://img.shields.io" />
</p>

A collection of my personal configurations for a hybrid workflow on Arch Linux, blending the elegance of **GNOME** with the efficiency of **Hyprland**.

## 📸 Showcase

### Hyprland (The Tiling Speedster)
![Hyprland Screenshot](./screenshots/hyprland.png)

### GNOME (The Polished Daily Driver)
![GNOME Screenshot](./screenshots/gnome.png)

## 🖥️ System Specs
| Component | Choice |
| :--- | :--- |
| **OS** | [Arch Linux](https://archlinux.org) |
| **WM** | [Hyprland](https://hyprland.org) |
| **DE** | [GNOME 4x](https://www.gnome.org) |
| **Terminal** | Kitty / Ghostty |
| **Shell** | Zsh (with Oh My Zsh) |
| **Bar** | Waybar |
| **Launcher** | Rofi / Wofi |

## 🚀 Installation

> [!WARNING]
> Always back up your existing configurations before applying new ones!

I use **GNU Stow** to manage these dotfiles.

1. **Clone the repo:**
   ```bash
   git clone https://github.com ~/dotfiles
   cd ~/dotfiles
   
2. **Apply Configurations:**
    stow hypr
    stow gnome
    stow nvim
    
3. **Keybindings (Hyprland):**
    Super + Q : Open Terminal
    Super + C : Kill Active window
    Super + M : Exit Hyprland
    Super + E : Open File Manager

