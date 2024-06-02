# my dotfiles

this is my config for my dev enviorment.

for i3, i used this tutorial to make its config [i3wm config playlist](https://www.youtube.com/playlist?list=PL0rXAycsylvXxyPDT5kGQ5MiHcqrZWv69)

# install required packages
```
sudo apt install i3 i3blocks lightdm-gtk-gretter rofi feh gnome-terminal stow -y
```
nvim may need to be compiled from source

# adding the dotfiles
you can use the stow command to add the dotfiles
```
stow .
```

# i3 theming

i use arc dark for my theme so make sure thats installed, the tutorial playlist tells how to install it.

to set the arc dark or other theme, run:
```
lxapperance
lightdm-gtk-gretter-settings
```
