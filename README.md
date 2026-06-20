# My i3 Dotfiles

 Custom i3 window manager setup on Debian, including: 
	
 - i3 config with Nordic theme, borders, and gaps
 - Custom i3status bar (CPU, RAM, load, disk, time)
 - Rofi launcher themed to match

 Managed with GNU Stow. To deploy on a fresh mahine:
 ```

 git clone git@github.com:FelipeCantu/dotfiles.git ~/dotfiles
 cd ~/dotfiles
 stow i3 rofi i3status
 ```

