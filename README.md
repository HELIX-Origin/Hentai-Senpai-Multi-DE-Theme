<div align="center">
<pre>
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║          ██╗  ██╗███████╗███╗   ██╗████████╗ █████╗ ██╗          ║
║          ██║  ██║██╔════╝████╗  ██║╚══██╔══╝██╔══██╗██║          ║
║          ███████║█████╗  ██╔██╗ ██║   ██║   ███████║██║          ║
║          ██╔══██║██╔══╝  ██║╚██╗██║   ██║   ██╔══██║██║          ║
║          ██║  ██║███████╗██║ ╚████║   ██║   ██║  ██║██║          ║
║          ╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝╚═╝          ║
║                                                                  ║
║          ███████╗███████╗███╗   ██╗██████╗  █████╗ ██╗           ║
║          ██╔════╝██╔════╝████╗  ██║██╔══██╗██╔══██╗██║           ║
║          ███████╗█████╗  ██╔██╗ ██║██████╔╝███████║██║           ║
║          ╚════██║██╔══╝  ██║╚██╗██║██╔═══╝ ██╔══██║██║           ║
║          ███████║███████╗██║ ╚████║██║     ██║  ██║██║           ║
║          ╚══════╝╚══════╝╚═╝  ╚═══╝╚═╝     ╚═╝  ╚═╝╚═╝           ║
║                                                                  ║
║          Multi-DE Theme • Nord Colors • Dark & Elegant           ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
</pre>
</div>

<h2 align="center">🐧 Supported Distributions</h2>

<p align="center">
  <a href="https://ubuntu.com"><img src="https://cdn.simpleicons.org/ubuntu/E95420" height="40" alt="Ubuntu" title="Ubuntu"></a>&nbsp;&nbsp;
  <a href="https://www.debian.org"><img src="https://cdn.simpleicons.org/debian/A81D33" height="40" alt="Debian" title="Debian"></a>&nbsp;&nbsp;
  <a href="https://getfedora.org"><img src="https://cdn.simpleicons.org/fedora/294172" height="40" alt="Fedora" title="Fedora"></a>&nbsp;&nbsp;
  <a href="https://archlinux.org"><img src="https://cdn.simpleicons.org/archlinux/1793D1" height="40" alt="Arch Linux" title="Arch Linux"></a>&nbsp;&nbsp;
  <a href="https://manjaro.org"><img src="https://cdn.simpleicons.org/manjaro/35BF5C" height="40" alt="Manjaro" title="Manjaro"></a>&nbsp;&nbsp;
  <a href="https://www.opensuse.org"><img src="https://cdn.simpleicons.org/opensuse/73BA25" height="40" alt="openSUSE" title="openSUSE"></a>&nbsp;&nbsp;
  <a href="https://linuxmint.com"><img src="https://cdn.simpleicons.org/linuxmint/87CF3E" height="40" alt="Linux Mint" title="Linux Mint"></a>&nbsp;&nbsp;
  <a href="https://pop.system76.com"><img src="https://cdn.simpleicons.org/popos/48B9C7" height="40" alt="Pop!_OS" title="Pop!_OS"></a>
</p>

<p align="center">A beautiful dark GTK theme based on <a href="https://github.com/vinceliuice/Orchis-theme">Orchis</a> with the elegant <a href="https://www.nordtheme.com/">Nord</a> color palette.</p>

![Theme Preview](images/preview-1.png)

## 📸 Gallery

<table>
  <tr>
    <td width="50%">
      <img src="images/preview-1.png" alt="Applications Preview" width="100%"/>
      <p align="center"><strong>Applications</strong> - GTK apps with the theme</p>
    </td>
    <td width="50%">
      <img src="images/preview-2.png" alt="Desktop Preview" width="100%"/>
      <p align="center"><strong>Desktop</strong> - Full desktop experience</p>
    </td>
  </tr>
</table>

## ✨ Features

- 🌙 **Dark & Elegant** — Deep blue-gray backgrounds with comfortable contrast
- 🎨 **Nord Colors** — Arctic-inspired color scheme designed for clarity
- 🔷 **Material Design** — Rounded corners, smooth shadows, ripple effects
- 🖥️ **Multi-DE Support** — GNOME, Cinnamon, XFCE, Budgie, and MATE
- 🎯 **Complete Theming** — GTK 2/3/4, GNOME Shell, window decorations, wallpapers
- ⚡ **Modern GTK4** — Full support for libadwaita-based applications
- 📦 **Flatpak Ready** — Theme support for sandboxed applications

## 🚀 Quick Start


Download the theme and CD into the root folder
```bash
git clone https://github.com/HELIX-Origin/Hentai-Senpai-Multi-DE-Theme.git
cd Hentai-Senpai-Multi-DE-Theme
```

Install with all recommended fixes
```bash
./install.sh --update -l -f --dock
```

Apply the theme
```bash
./scripts/apply.sh
```

## 📋 Requirements

- GTK 3.20+ or GTK 4.0+
- GNOME Shell 40+ (for GNOME users)
- Bash 4.0+

💾 Installation

Basic install
```bash
./install.sh
```

Complete install (recommended) - includes GTK4, Flatpak, and dock fixes
```bash
./install.sh --update -l -f --dock
```

### ⚙️ Installation Options

| Option | Short | Description |
|--------|-------|-------------|
| `--update` | | Update/reinstall theme |
| `--uninstall` | `-u` | Remove theme |
| `--libadwaita` | `-l` | Fix GTK4/libadwaita apps |
| `--flatpak` | `-f` | Fix Flatpak apps |
| `--dock [TYPE]` | | Dock theme (transparent/solid) |
| `--wallpapers` | `-w` | Install wallpapers |

## 🔧 Quick Fixes

- 💡 **GTK4 apps not themed?** `./install.sh -l` then log out and back in
- 💡 **Flatpak apps not themed?** `./install.sh -f` then restart Flatpak apps
- 💡 **Dock not styled?** `./install.sh --dock transparent` or `--dock solid`

- 🐛 [Report bugs](https://github.com/HELIX-Origin/Hentai-Senpai-Multi-DE-Theme/issues)
- ✨ [Suggest features](https://github.com/HELIX-Origin/Hentai-Senpai-Multi-DE-Theme/discussions)
- 📝 Improve documentation

## 🙏 Credits

- 🎨 Based on [Orchis Theme](https://github.com/vinceliuice/Orchis-theme) by vinceliuice
- 🌈 [Nord Theme](https://www.nordtheme.com/) color palette by Arctic Ice Studio

## 📄 License

⚖️ GPL-3.0 License — see [LICENSE](https://github.com/HELIX-Origin/Hentai-Senpai-Multi-DE-Theme/blob/main/LICENSE) file for details.

---

🎨 **Enjoy your new theme!**
