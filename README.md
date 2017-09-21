# jgd-cobalt-blue
JGD-CobaltBlue is based on the design for [JGD-Black](http://www.jasong-designs.com/2017/02/04/jgd-black-gtk3/). It sports tints of the color Cobalt Blue (hex color #0020c2). GTK 3.20+, GTK 2, and Openbox themes are included with this package.
* [Theme homepage at Jason G. Designs](http://www.jasong-designs.com/2017/09/19/jgd-cobaltblue/)
## How to Install
1. Download the latest file from the [downloads](https://github.com/jgpws/jgd-cobalt-blue/tree/master/downloads) directory
2. Open a Terminal application in Linux
3. Navigate to your Downloads folder in the terminal (usually titled Downloads). Type `cd Downloads`
4. Type `ls` and look for `jgd-cobaltblue-month-day-year.tar.gz`, where month, day and year represent when the file was last updated
5. Untar the file by typing `tar -zxvf jgd-cobaltblue-01-01-17.tar.gz`, substituting the current version's date numbers
6. type `cd` again to get to your home folder; type `ls -a` and see if there is a **.themes** directory
7. If one does not exist, create one: `mkdir .themes`
8. `cd Downloads`
9. `cp JGD-CobaltBlue ../.themes`
### To Install JGD-CobaltBlue globally:
1. Follow steps 1-5 above
2. `cd /usr/share/themes`
3. `sudo cp -r ~/Downloads/JGD-CobaltBlue /usr/share/themes`
4. Enter sudo password
5. `ls` to check that the theme folder is present
### To Install on Arch Linux:
JGD-CobaltBlue is available in the Arch User Repository. The easiest way to install it is with a pacman frontend which accesses the AUR, such as [Yaourt](https://archlinux.fr/yaourt-en).

`yaourt -S jgd-cobaltblue`

Once installed, you can use a theme switching application such as **LXAppearance** or **Gnome Tweak Tool** to change the theme to JGD-Black
## How to install the Clearlooks theme engine
JGD-CobaltBlue, like JGD-Black, requires the Clearlooks GTK2 theme engine. To install:
### Ubuntu and derivatives:
`apt-get install gtk-engines`
### Arch Linux and derivatives:
`sudo pacman -S gtk-engines`
Note: The GTK3 version of this theme only works in version 3.20 and upwards.
