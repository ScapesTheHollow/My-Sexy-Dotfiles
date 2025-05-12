

# ✨ My Sexy Dotfiles - Arch Linux + Hyprland Setup

These are my personal dotfiles for Arch Linux using Hyprland. Includes configs for window managers, terminals, apps, and CLI tools — built for aesthetics and efficiency.

---

## 🚀 Quick Start (for stow-based setup)

1. Clone the repo:

```bash
git clone https://github.com/ScapesTheHollow/My-Sexy-Dotfiles.git ~/Dotfiles
cd ~/Dotfiles
````

2. Stow the configs:

```bash
stow .
```

This will symlink all the dotfiles into your `$HOME` directory automatically.

> 📦 Make sure `stow` is installed first with:

```bash
sudo pacman -S stow
```

---

## 🧱 Install My Base Packages

On a fresh Arch system, run this to install all my essential apps:

```bash
sudo pacman -S stow vesktop spotify zen-browser ani-cli cava cmatrix asciiquarium libreoffice neovim btop obsidian anki zathura zotero yazi amberol qbittorrent visual-studio-code-bin
```

> 🔔 Some packages like `vesktop`, `spotify`, `zen-browser`, and `visual-studio-code-bin` are from the **AUR**.
> Use an AUR helper like `yay` or `paru` to install them:

```bash
yay -S vesktop spotify zen-browser visual-studio-code-bin
```

---

## 🔥 Tools & Themes Used

* 🪟 **Window Manager**: Hyprland
* 🖥️ **Bar**: Waybar
* 🖋️ **Terminal**: Kitty
* 📁 **File Manager**: Yazi
* ✨ **Editor**: Neovim, VS Code
* 🧠 **Knowledge**: Obsidian, Zotero, Zathura, Anki
* 🎵 **Audio**: Amberol, Cava
* 🐠 **CLI Fun**: cmatrix, asciiquarium

---

## 📚 License

MIT — Feel free to fork, steal, or remix.

```
