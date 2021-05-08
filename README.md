# Alabaster theme for Xresources

A light color scheme for X11 based applications like xterm and (u)rxvt.

Based on the [Alabaster Sublime Scheme](https://github.com/tonsky/sublime-scheme-alabaster) by Nikita Prokopov


## Installation

### Manual
Copy the contents of the [`alabaster`](https://github.com/anmolmathias/xresources-alabaster/blob/main/src/alabaster) file into the `~/.Xresources` or `~/.Xdefaults` file and reload the settings with `xrdb`.

### Via `#include`
Copy the [`alabaster`](https://github.com/anmolmathias/xresources-alabaster/blob/main/src/alabaster) file to any place and import it via `#include "/path/to/nord"`.

### Via `merge`
To merge the color theme into your current settings copy the [`alabaster`](https://github.com/anmolmathias/xresources-alabaster/blob/main/src/alabaster) file to any place and run `xrdb -merge path/to/nord`.

## License

[MIT License](./LICENSE)
