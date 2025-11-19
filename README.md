reference from https://github.com/mahkoh/xdg-desktop-portal-gtk4

i use this for linux mint 22.2

```diff
sudo dpkg -i xdg-desktop-portal-gtk4_1.0-1_amd64.deb
```

make file config /usr/share/xdg-desktop-portal/portals.conf or ~/.config/xdg-desktop-portal/portals.conf

```diff
[preferred]
default=gtk
org.freedesktop.impl.portal.FileChooser=gtk4
```

restart pc, done

darkmode (optional)
```diff
gsettings set org.gnome.desktop.interface color-scheme 'prefer-dark'
```
