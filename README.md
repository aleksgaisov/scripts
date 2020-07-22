# Scripts

This is a collection of custom bash scripts that are being utilized on a daily basis (some more than others).

Some of the scripts are not entirely written by me. These scripts have an appropriate source link in their description.

### The repo _currently_ includes the following scripts:
(_Some scripts may require dependences. You can also find them in the list below._)

* calcurse-notify
  * spawn notifications for the calcurse calendar app
  * _Depends on:_ calcurse
* corona
  * prints out the recent COVID-19 data inside the terminal
  * [Source](https://github.com/sagarkarira/coronavirus-tracker-cli)
* device-manager
  * mount/unmount devices through dmenu app (default dwm theme)
  * _Depends on:_ dmenu
* device-manager_isotope
  * mount/unmount devices through dmenu app (isotope theme theme)
  * _Depends on:_ dmenu
* device-manager_solarized
  * mount/unmount devices through dmenu app (solarized theme)
  * _Depends on:_ dmenu
* dobackup
  * backup script for important files/dirs inside the home folder
* gtd
  * get-things-done 'pomodoro timer'
  * [Source](https://github.com/sagarkarira/coronavirus-tracker-cli)
* i3lock-mod
  * i3lock modification that sets the pixilized screenshot as a lock background
  * _Depends on:_ i3lock, scrot, imagemagick
* monitor-switch
  * toggles the visual output between default/duplicate/external each execution
  * _Depends on:_ xorg-xrandr
* restart-dwmblocks
  * restarts [dwmblocks](https://github.com/torrinfail/dwmblocks) status bar
  * _Depends on:_ dwmblocks
* screen-blank
  * sets the screen off until triggered
  * _Depends on:_ xorg-xset
* session-manager
  * lock/reboot/shutdown the machine throuth dmenu app (default dwm theme)
  * _Depends on:_ dmenu, i3lock-mod (see above)
* session-manager_isotope
  * lock/reboot/shutdown the machine throuth dmenu app (isotope theme)
  * _Depends on:_ dmenu, i3lock-mod (see above)
* session-manager_solarized
  * lock/reboot/shutdown the machine throuth dmenu app (solarized theme)
  * _Depends on:_ dmenu, i3lock-mod (see above)
* startx-manager
  * if ran in a tty, allows to choose between different visual environments to be loaded
  * _Depends on:_ xorg-server, xorg-init
* toggle-touchpad
  * toggle touchpad (or any other input device, for that matter) on/off
  * _Depends on:_ xorg-input
* wallpaper-changer
  * used to set a given or a random wallpaper
  * _Depends on:_ feh
* weather
  * prints out a  weather report inside the terminal
  * [Source](https://github.com/chubin/wttr.in)
* wifi-connect
  * used for connecting to a wireless network
  * _Depends on:_ networkmanager
