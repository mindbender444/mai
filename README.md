<h1 align="center">
  Mindbender's <a href=https://www.archlinux.org/>Archlinux</a> Installer
</h1>
<h4 align="center">Forked on 10-13-2020 from <a href=https://github.com/helmuthdu/aui/>aui</a> by mindbender444. I recommend to use the original version by helmuthdu as this one is probably broke...</h4>

## Note
* You can first try it in a `VirtualMachine`

## Prerequisites

- A working internet connection
- Logged in as 'root'

## Obtaining The Repository
### With git
- Increase cowspace partition: `mount -o remount,size=2G /run/archiso/cowspace`
- Get list of packages and install git: `pacman -Sy git`
- Get the script: `git clone git://github.com/mindbender444/aui`

### Without git
- Increase cowspace partition: `mount -o remount,size=2G /run/archiso/cowspace`
- Get the script: ` wget https://github.com/mindbender444/aui/tarball/master -O - | tar xz`

    <!-- - an alternate URL (for less typing (github shorten)) is ` wget https://git.io/vS1GH -O - | tar xz`
    - an alternate URL (for less typing) is ` wget http://bit.ly/NoUPC6 -O - | tar xz`
    - super short `wget ow.ly/wnFgh -O aui.zip` -->

## How to use
- FIFO [System Base]: `cd aui ; ./fifo`
- LILO [The Rest]: `cd aui ; ./lilo`

## Features
### FIFO SCRIPT
- Configure keymap
- Select editor
- Automatic configure mirrorlist
- Create partition
- Format device
- Install system base
- Configure fstab
- Configure hostname
- Configure timezone
- Configure hardware clock
- Configure locale
- Configure mkinitcpio
- Install/Configure bootloader
- Configure mirrorlist
- Configure root password

### LILO SCRIPT
- Backup all modified files
- Install additional repositories
- Create and configure new user
- Install and configure sudo
- Automatic enable services in systemd
- Install an AUR Helper [trizen, yay...]
- Install Base System
- Install systemd
- Install Preload
- Install Zram
- Install Xorg
- Install GPU Drivers
- Install CUPS
- Install Additional wireless/bluetooth firmwares
- Ensuring access to GIT through a firewall
- Install DE or WM [Cinnamon, Enlightenment, FluxBox, GNOME, i3, KDE, LXDE, OpenBox, XFCE...]
- Install Developement tools [Vim, Emacs, Eclipse...]
- Install Office apps [LibreOffice, GNOME-Office, Latex...]
- Install System tools [Wine, Virtualbox, Grsync, Htop...]
- Install Graphics apps [Inkscape, Gimp, Blender, MComix...]
- Install Internet apps [Firefox, Google-Chrome, Jdownloader...]
- Install Multimedia apps [Rhythmbox, Clementine, Codecs...]
- Install Games [Desura, PlayOnLinux, Steam, Minecraft...]
- Install Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Install and configure Web Servers
- And Many More...


## Thank helmuthdu
If you like my work, please consider a small Paypal donation at helmuthdu@gmail.com :)

## License :scroll:
This project is licenced under the GNU General Public License V3. For more information, see the `LICENSE` file or visit https://www.gnu.org/licenses/gpl-3.0.en.html.
