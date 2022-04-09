# Pop!OS Post Install Guide
Things to do after installing Pop!OS

## Dns 
* cloudflare

## Update
* `sudo apt update && sudo apt upgrade`
* `sudo apt full-upgrade && sudo apt dist upgrade`
* `sudo apt autoremove && sudo apt autoclean`
* `flatpak update`
* reboot

## Change Hostname
* `hostnamectl set-hostname YOUR_HOSTNAME`

## Codecs
* `sudo apt install libavcodec-extra ubuntu-restricted-extras`

## Go through Settings
* Check all the settings and configure as needed.

## Get Stock Gnome (if you want to)
* Turn off cosmic gnome extensions 
* `sudo apt install gnome-sesssion`
* Log out and switch to gnome from the cog wheel

## Firefox
* `git clone https://github.com/EliverLara/firefox-nordic-theme && cd firefox-nordic-theme`
* `./scripts/install.sh -g -p *.default-release`
* also set 
media.ffmpeg.vaapi.enabled: true
media.rdd-vpx.enabled : true

## Theming 

### GTK Themes
* https://www.gnome-look.org/p/1280977/
* https://github.com/lassekongo83/adw-gtk3
* https://github.com/vinceliuice/Colloid-gtk-theme 
* https://github.com/EliverLara/Nordic
* https://github.com/vinceliuice/Orchis-theme
* https://github.com/vinceliuice/Graphite-gtk-theme

### Use themes in Flatpaks
* `sudo flatpak override --filesystem=$HOME/.themes`
* `sudo flatpak override --env=GTK_THEME=my-theme`

### Fonts
* `sudo apt install fonts-cantarell` 

### Icons
* https://github.com/vinceliuice/Tela-icon-theme
* https://github.com/vinceliuice/Colloid-gtk-theme/tree/main/icon-theme

### Walpapers
* https://github.com/manishprivet/dynamic-gnome-wallpapers

### Grub Theme
* https://github.com/vinceliuice/grub2-themes

### Gnome-Shell extensions
* [Extensions Sync](https://extensions.gnome.org/extension/1486/extensions-sync/)
* [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
* [Just Perfection](https://extensions.gnome.org/extension/3843/just-perfection/)
* [Net Speed Simplified](https://extensions.gnome.org/extension/3724/net-speed-simplified/)
* [Gsconnect](https://extensions.gnome.org/extension/1319/gsconnect/)
* [Bluetooth Quick Connect](https://extensions.gnome.org/extension/1401/bluetooth-quick-connect/)
* [Input Output Device Chooser](https://github.com/mmalafaia/gse-sound-output-device-chooser/tree/patch-1)
* [Clipboard Indicator](https://extensions.gnome.org/extension/779/clipboard-indicator/)
* [Blur My Shell](https://extensions.gnome.org/extension/3193/blur-my-shell/)

## Packages
* Deja Dup 
* Ulauncher
* Blanket
* Atom
* Krita 
* Pitivi
* Joplin
* Fragments
