`sudo apt update`
`sudo dpkg -i path_to_.deb_file` # install deb-package
`sudo dpkg -r program_name` # remove

`gsettings set org.gnome.desktop.peripherals.touchpad send-events disabled-on-external-mouse` # disable touchpad when mouse is enabled
`gsettings set org.gnome.desktop.peripherals.touchpad send-events enabled` # undo
`gsettings set org.gnome.desktop.peripherals.touchpad disable-while-typing true` # disable the touchpad when the mouse is off, but when printing text
`gsettings set org.gnome.desktop.peripherals.touchpad disable-while-typing false` # undo