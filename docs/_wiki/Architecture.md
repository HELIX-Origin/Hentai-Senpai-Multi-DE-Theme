---
layout: wiki
title: Theme Architecture
summary: Component hierarchy and styling targets across GTK toolkits and desktop window managers.
parent: Technical Wiki & Reference
---

## 🏛️ Toolkit Coverage

The theme provides cohesive stylesheets across all major Linux graphical toolkits:

| Toolkit / Component | Target Files | Engine / Format |
| :--- | :--- | :--- |
| **GTK 2.0** | `gtk-2.0/gtkrc`, `gtk-2.0/main.rc` | Murrine / Pixmap engine |
| **GTK 3.0** | `gtk-3.0/gtk.css`, `gtk-3.0/gtk-dark.css` | CSS3 / GtkStyleProvider |
| **GTK 4.0 / libadwaita** | `gtk-4.0/gtk.css` | Modern CSS / libadwaita overrides |
| **GNOME Shell** | `gnome-shell/gnome-shell.css` | St CSS / Mutter compositor |
| **Cinnamon** | `cinnamon/cinnamon.css` | Clutter / Muffin compositor |
| **XFCE / XFWM4** | `xfwm4/themerc` | XFWM4 pixmap decoration |
| **Metacity** | `metacity-1/metacity-theme-3.xml` | XML vector / Metacity frames |
{: .surfaces-table}

---

## 📁 Source Layout

Theme SCSS sources reside in `src/` and compile via Sass into standalone CSS bundles for distribution.
