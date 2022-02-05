# Pop!OS Post Install Guide
Things to do after installing Pop!OS

## Update
* Go into Pop!Shop, click on installed and then update all
* OR
* `sudo apt update && sudo apt upgrade`
* `sudo apt autoremove && sudo apt autoclean`
* `sudo fwupdmgr update`
* `flatpak update`
* reboot

## Restricted Extras
* `sudo apt install ubuntu-restricted-extras`

## Change Hostname
* `hostnamectl set-hostname YOUR_HOSTNAME`

## Codecs
* `sudo apt install -y libavcodec-extra libdvd-pkg; sudo dpkg-reconfigure libdvd-pkg`

## Go through Settings
* Check all the settings and configure as needed.

## Themeing 

### GTK Themes
* https://github.com/vinceliuice/Colloid-gtk-theme 
* https://github.com/EliverLara/Nordic
* https://github.com/vinceliuice/Orchis-theme
* https://github.com/vinceliuice/Graphite-gtk-theme

### Use themes in Flatpaks
* `sudo flatpak override --filesystem=$HOME/.themes`
* `sudo flatpak override --env=GTK_THEME=my-theme`

### Icons
* https://github.com/vinceliuice/Tela-icon-theme
* https://github.com/vinceliuice/Colloid-gtk-theme/tree/main/icon-theme

### Grub Theme
* https://github.com/vinceliuice/grub2-themes

## Gnome-Shell extensions
* [Extensions Sync](https://extensions.gnome.org/extension/1486/extensions-sync/)
* [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
* [Just Perfection](https://extensions.gnome.org/extension/3843/just-perfection/)
* [Net Speed Simplified](https://extensions.gnome.org/extension/3724/net-speed-simplified/)
* [Gsconnect](https://extensions.gnome.org/extension/1319/gsconnect/)
* [Bluetooth Quick Connect](https://extensions.gnome.org/extension/1401/bluetooth-quick-connect/)
* [Input Output Device Chooser](https://github.com/mmalafaia/gse-sound-output-device-chooser/tree/patch-1)
