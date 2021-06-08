# Spotify plugin for tmux

![2021-06-08 20 11 42](https://user-images.githubusercontent.com/72242664/121208487-4bfd1100-c8a4-11eb-98a0-8d8c638226f2.gif)

## Installation

### Using Tmux Plugin Manager

Add the plugin in `.tmux.conf`

```
set -g @plugin 'tatthien/tmux-spotify'
```

Press `prefix` + `I` to fetch the plugin and source it.

## Usage

Add `#{spotify}` somewhere that you prefer in the righ status line:

```
set-option -g status-right "#{spotify}"
```

Then you'll see something like `♫ Artist name - Track name` in the status line.

## Credit

This plugin cannot go live without helps from existent plugins/scripts.

- [tmux-weather](https://github.com/xamut/tmux-weather)
- [tmux-spotify-info](https://github.com/jdxcode/tmux-spotify-info)
