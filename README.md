# My i3 Dotfiles

 Custom i3 window manager setup on Debian, including: 
	
 - i3 config with Nordic theme, borders, and gaps
 - Custom i3status bar (CPU, RAM, load, disk, time)
 - Rofi launcher themed to match
 - Picom launcher themed to match
 - Dunst notification daemon, Nordic-themed

 Managed with GNU Stow. To deploy on a fresh mahine:

 ## Notes
 - Picom uses the 'xrender' backend instead of 'glx' /GPU acceleration, since VirtualBox's
   virtual graphics driver doesn't reliably supoort GLX. If runnning on real hardware,
   `glx` may give better preformance.
 - `i3status` config is still present in this repo but no longer in active use 
   polybar replaced it as the primary status bar.

 ## Deploy on a fresh machine
 ```

 git clone git@github.com:FelipeCantu/dotfiles.git ~/dotfiles
 cd ~/dotfiles
 stow i3 rofi i3status
 ```

