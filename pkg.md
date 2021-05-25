# Workstation

Ubuntu 21.04 (Minimal installation)
Gnome 3.38

## snapd

Remove snapd completely

```
snap list
```

```
sudo snap remove --purge package-name
```

```
sudo rm -rf /var/cache/snapd/
```

```
sudo apt autoremove --purge snapd
```

```
rm -fr ~/snap
```

```
sudo apt-mark hold snapd
```

## apt

* vim
* git
* tree
* neofetch
* preload
* build-essential
* golang
* nodejs
* npm
* flatpak

## flatpak

`flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`

* org.mozilla.firefox
* org.chromium.Chromium
* com.discordapp.Discord
* com.microsoft.Teams
* io.atom.Atom
* org.libreoffice.LibreOffice
* com.github.fabiocolacio.marker
* com.obsproject.Studio
* org.gimp.GIMP
* org.videolan.VLC
* com.system76.Popsicle
* com.valvesoftware.Steam
* com.mojang.Minecraft

## firefox

### Home
- Web Search
- ~~Top Sites~~
- ~~Highlights~~
- ~~Snippets~~

### Search
- Default Search Engine: DuckDuckGo
- Search Shortcuts: [DuckDuckGo, Google, Bing, Bookmarks, Tabs, History]

### Privacy & Security
- HTTPS-Only Mode: Enable HTTPS-Only Mode in all windows









