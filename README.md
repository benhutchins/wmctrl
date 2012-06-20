wmctrl.py
======

A simpler Python script to add Windows-7 like shortcuts to Linux.

This application relies on wmctrl, ensure you have it installed before use.

    sudo apt-get install wmctrl xdotool

Add keyboard shortcuts calling a command from the list below like:

    python wmctrl.py left

Available commands are:

    command           | description                                                   | recommended shortcut
    --------------------------------------------------------------------------------------------------------
    left                Position active window on the left-half of your desktop.        Super+Left
    right               Position active window on the right-half of your desktop        Super+Right
    up                  Toggle maximized state of active window (TODO)                  Super+Up
    down                Demaximize window if maximized, if not, minimize window.        Super+Down
    shift-left          Position window to take up 1/3 or 2/3 of desktop on left.       Super+Shift+Left
    shift-right         Position window to take up 1/3 or 2/3 of desktop on right.      Super+Shift+Right
    shift-up            Position a window to take up 1/2 of desktop on top.             Super+Shift+Up
    shift-down          Position a window to take up 1/2 of desktop on bottom.          Super+Shift+Down
