---
layout: docs
title: Installation & Updates
summary: Learn how to run the interactive installer, pass automated command-line flags, and maintain theme updates.
parent: Documentation Directory
---

## 🚀 Quick Install

To clone the repository and run the recommended complete installation:

```bash
git clone https://github.com/HELIX-Origin/Hentai-Senpai-Multi-DE-Theme.git
cd Hentai-Senpai-Multi-DE-Theme
./install.sh --update -l -f --dock
```

Then apply the theme:

```bash
./scripts/apply.sh
```

---

## ⚙️ Installer Options

The `install.sh` script supports flexible flags for customization:

| Flag | Description |
| :--- | :--- |
| `-d, --dest DIR` | Specify custom destination directory (default: `~/.themes`) |
| `-n, --name NAME` | Specify custom theme name (default: `Hentai-Senpai`) |
| `-t, --theme VARIANT` | Install specific theme variants |
| `-c, --color ACCENT` | Install specific accent colors (standard Nord frost) |
| `-l, --libadwaita` | Link theme to `~/.config/gtk-4.0` for GTK4/libadwaita apps |
| `-f, --flatpak` | Link theme into Flatpak overrides so sandboxed apps are themed |
| `--dock` | Patch and style Dash to Dock / Ubuntu Dock extension |
| `-u, --update` | Check for updates and reinstall latest version |
| `-r, --remove` | Remove all installed theme files cleanly |
{: .surfaces-table}

---

## 📦 Libadwaita & GTK4 Applications

Modern GNOME apps use `libadwaita`, which bypasses user GTK themes by default. Passing `-l` or `--libadwaita` symlinks the theme CSS directly into `~/.config/gtk-4.0/gtk.css`, ensuring full dark Nord styling across all native GNOME apps.

## 🛡️ Flatpak Sandboxed Apps

Flatpak applications run in isolated containers. Passing `-f` or `--flatpak` grants container read access to `~/.themes` via `flatpak override --filesystem=xdg-data/themes`, harmonizing sandboxed apps with your desktop.
