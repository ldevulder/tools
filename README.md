# Tools

Place to save different tools I made and use daily.

## Flatpak useful tricks

- Force X11 instead of Wayland:
```sh
$ flatpak override --nosocket=wayland --socket=x11 <yourapp>
```

## start_x11

Wrapper to run "buggy" X11 application with Xwayland in rootful mode.

## create_uc_image

Tool to help creation of OS image with Elemental3.
