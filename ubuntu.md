# Awesome Ubuntu Cheatsheet

`sudo apt update`<br>
`sudo dpkg -i path_to_.deb_file` # install deb-package<br>
`sudo dpkg -r program_name` # remove<br>

`gsettings set org.gnome.desktop.peripherals.touchpad send-events disabled-on-external-mouse` # disable touchpad when mouse is enabled<br>
`gsettings set org.gnome.desktop.peripherals.touchpad send-events enabled` # undo<br>
`gsettings set org.gnome.desktop.peripherals.touchpad disable-while-typing true` # disable the touchpad when the mouse is off, but when printing text<br>
`gsettings set org.gnome.desktop.peripherals.touchpad disable-while-typing false` # undo<br>