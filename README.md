# orangini
Orangini is a GTK-theme

![s](https://cn.pling.com/img/f/a/7/2/e4f5ed94d4bd967d2853078655b5e9231d5a.jpg)

This is a first (all-be-it thoroughly checked) draft of a theme on my way to a completely new theme for Ubuntu 18.04. The beauty is in the details, as I have spend a great deal of theme on finetuning it to work accross GTK-2 and GTK-3 applications.

This theme is developed on gnome 3.20 and updated to 3.28
This only works on a gnome-desktop, no support for other desktop-environments.
It also works on Ubuntu 17.10

### requirements

When, as such, theming does not look the way it should be: make sure you have installed the necessary theme-"engines":

- The gnome-themes-standard package,
- The murrine engine. This has different names depending on your distro.
gtk-engine-murrine (Arch Linux)
gtk2-engines-murrine (Debian, Ubuntu, elementary OS)
gtk-murrine-engine (Fedora)
gtk2-engine-murrine (openSUSE)
gtk-engines-murrine (Gentoo)

sudo apt-get install gtk2-engines-pixbuf

### How to install:

First: Just copy the extracted file to a '.themes'-folder you make in your home directory, or better copy to /usr/share/themes for system-wide use.
Then use Tweak-tool to select the GTK.
LOG OUT AND BACK IN for changes to take effect !

Second: Orangini uses titlebuttons on the right-side:
To put the buttons to the left open a terminal:

gsettings set org.gnome.desktop.wm.preferences button-layout ":minimize,maximize,close"

In Gnome 3.26+ gnome-tweak has a option to change the position of the titlebuttons, so the above steps are not necessary.

