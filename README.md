# Ultimate-Arch-Cleaner

>Script to clean your archlinux. Removal of the yogurt, pacman and flatpak cache. Update of mirrors compared to the most efficient French servers. The script cleans up directories which can be automated but does not take configuration files into account. Since this is sensitive data, I advise you to do it by hand. I provide in the description the list of directories to check to remove the remainder of your applications.

[![Capture-d-cran-du-2024-04-08-15-24-19.png](https://i.postimg.cc/SRDfFZ8p/Capture-d-cran-du-2024-04-08-15-24-19.png)](https://postimg.cc/zHHgTF0d)

### Requirements

- [yay](https://github.com/Jguer/yay)
- [reflector](https://wiki.archlinux.org/title/Reflector)

### Features provided

- removing orphan packages
- pacman cache deletion
- yay cache deletion
- apps cache deletion
- flatpak cache deletion
- logs deletion
- fr mirror list update
- full update and upgrade

### Installation

```
mkdir  ~/.local/tmp/
cd ~/.local/tmp/
git clone https://github.com/TheCyberArcher/Ultimate-Arch-Cleaner.git
cd Ultimate-Arch-Cleaner
sudo bash Ultimate-Arch-Cleaner.sh
``` 

### Config files to remove manually

```
~/.config/"appname"
~/.local/share/"appname"
/etc/"appname"
/usr/share/"appname"
/usr/share/applications/"appname"
/etc/xdg/autostart/"appname"

/var/lib/flatpak/"appname"
/var/lib/flatpak/runtine/"appname"
```
