# .dotfiles

## Setup

To create the sim-links for manjaro:
```
stow -d manjaro -t ~ .
```

## Packages

Install the basics:
```
sudo apt install i3 i3blocks i3blocks-contrib
sudo apt install git gitg tig
sudo apt install stow
sudo apt install zsh lxappearance gtk-chtheme
sudo apt install curl wget net-tools htop nmap
sudo apt install pavucontrol pasystray blueman xfce4-power-manager arandr numlockx playerctl xbacklight brightnessctl
sudo apt install python-pip3
sudo apt install minicom wireshark vim fzf feh
```

List of other useful packages to install:
- [oh-my-zsh](https://ohmyz.sh/)
- [VirtualBox](https://www.virtualbox.org/)
- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Poetry](https://python-poetry.org/)
- [binwalk](https://github.com/ReFirmLabs/binwalk)
- [k9s](https://k9scli.io/)
- [DisplayLink](https://www.synaptics.com/products/displaylink-graphics/downloads)
- [yEd](https://www.yworks.com/products/yed)
- [VLC media player](https://www.videolan.org/vlc/):
  ```
  sudo apt install vlc
  ```
- [Shutter](https://shutter-project.org/)
  ```
  sudo apt install shutter
  ```
- [Filelight](https://apps.kde.org/nl/filelight/)
  ```
  sudo apt install filelight
  ```
- [Dolphin](https://apps.kde.org/nl/dolphin/)
- [Kate](https://kate-editor.org/en-gb/)

List of browsers:
- [Google Chrome](https://www.google.com/intl/en_uk/chrome/)
- [Brave](https://brave.com/)

List of code editors:
- [Visual Studio Code](https://code.visualstudio.com/)
- [Intellij IDEA](https://www.jetbrains.com/idea/)
- [PyCharm](https://www.jetbrains.com/pycharm/)

List of PDF viewers/editors:
- [Okular](https://okular.kde.org/)
- [Xournal++](https://xournalpp.github.io/)

List of tools for images manipulation:
- [GIMP](https://www.gimp.org/):
  ```
  sudo apt install gimp
  ```
- [Inkscape](https://inkscape.org/):
  ```
  sudo apt install inkscape
  ```
- [Pinta](https://www.pinta-project.com/):
  ```
  sudo apt install pinta
  ```
- [Kolourpaint](https://apps.kde.org/nl/kolourpaint/)
  ```
  sudo apt install kolourpaint
  ```
- [ImageMagick](https://imagemagick.org/index.php)
  ```
  sudo apt install imagemagick
  ```

List of leasure tools:
- [Spotify](https://www.spotify.com/us/download/other/)

## Other

### Touchpad settings

Change the touchpad settings by copying file [`41-libinput-extra.conf`](41-libinput-extra.conf) to `/usr/share/X11/xorg.conf.d/`.
