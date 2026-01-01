# WSelector

___Wallpaper Selector Manager___

WSelector is a modern GTK4/libadwaita application that allows users to browse and set wallpapers from Wallhaven.cc. It features a clean, responsive interface with support for searching, filtering, and previewing wallpapers before setting them. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.github.Cookiiieee.WSelector
flatpak run io.github.Cookiiieee.WSelector
```

## Building

```
git clone git@github.com:flathub/io.github.Cookiiieee.WSelector.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.Cookiiieee.WSelector.json
```

---

**Technologies**: GNOME, GTK4, libadwaita, Python
