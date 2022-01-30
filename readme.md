# 


![enter image description here](https://github.com/shikikan-neko08/dotfiles-nord/blob/batik/screenshots/2022-01-29-172110_1366x768_scrot.png)

![enter image description here](https://github.com/shikikan-neko08/dotfiles-nord/blob/batik/screenshots/2022-01-29-173059_1366x768_scrot.png)

![enter image description here](https://github.com/shikikan-neko08/dotfiles-nord/blob/batik/screenshots/2022-01-29-173108_1366x768_scrot.png) 

![enter image description here](https://github.com/shikikan-neko08/dotfiles-nord/blob/batik/screenshots/2022-01-29-174403_1366x768_scrot.png)




# Details
* Font Used : Iosevka Term SS01
* GTK Theme : [Nordic-bluish-accent (GTK2/3) ](https://github.com/EliverLara/Nordic/releasess) . I'll call it frostneko
* Icons     : [NordArc](https://www.gnome-look.org/p/1427194/)
* OS        : Artix Linux
* WM        : BSPWM
* Terminal  : Kitty
* Shell     : zsh
* Bar       : Polybar
* Lockscreen: betterlockscreen

# Dependecies
 * [rofi](https://github.com/davatorium/rofi)
 * [kitty](https://github.com/kovidgoyal/kitty)
 * [bspwm](https://github.com/baskerville/bspwm) 
 * [Polybar](https://github.com/polybar/polybar)
 * [betterlockscreen](https://github.com/pavanjadhaw/betterlockscreen)   
 * nitrogen 
 * Font Awesome
 * [clearine](https://github.com/okitavera/clearine)
 * Imagemagick
 
  Some of this packages might not be available on your distro's repository, please refer to your distro package manager.
  For Arch-based users, you may use AUR for those packages.
  
# Installation

**Important : Make sure to backup your existing configuration files before installing to avoid loss**     

* Install the dependencies
* Clone this repository
* Install [powerlevel10k](https://github.com/romkatv/powerlevel10k)
* copy powerlevel10k.zsh-theme to your powerlevel10k folder
* copy .p10k.zsh to your home directory.
* install the required fonts by copying .fonts directory to your home directory      
> **Note : forttf-font-awesome, install it from your repository**          
> **Arch : sudo pacman -S ttf-font-awesome**
* copy all .config files to your .config directory
* copy all .themes, .icons folders to your home directory
* install oh-my zsh then manually then move .zshrc into your home directory
* install pywal and move .cache/wal into your .cache directory
* install [vim-plug](https://github.com/junegunn/vim-plug)
* copy vimrc into .vim directory
* manually install the plug by opening vimrc using vim then instal the plugin using :PlugInstall   
* Set the wallpaper using nitrogen  
* Set Lockscreen Wallpaper using this command      
> betterlockscreen -u /path/to/wallpaper.png

To apply The GTK Theme and icons, you can use LXappearance    

# Notes
* If you are installing this on systemd , don't forget to change the loginctl
 command to systemctl on clearine.conf and polybar config
* Polybar is disabled by default. to enable it run "launchbar" if you are on zsh shell. or uncomment the launch.sh on i3/config. this only affect i3 users. user that using bspwm as their default didn't need to configure this as the polybar is executed during startup


# License

GPL 3.0
