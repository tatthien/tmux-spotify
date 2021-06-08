# Spotify plugin for tmux

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
