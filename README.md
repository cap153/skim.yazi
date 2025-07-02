# skim.yazi

[skim](https://github.com/skim-rs/skim) plugin for [Yazi](https://github.com/sxyazi/yazi).

# Dependencies

* [`skim`](https://github.com/skim-rs/skim)
* [`fd`](https://github.com/sharkdp/fd])
* [`bat`](https://github.com/sharkdp/bat)

## Installation

```sh
ya pkg add cap153/skim
```

## Usage

Add this to your `~/.config/yazi/keymap.toml`:

```toml
[[mgr.prepend_keymap]]
on  = "<C-t>"
run = "plugin skim"
```

Available keybindings:

| Key binding            | Alternate key | Action                      |
|------------------------|---------------|-----------------------------|
| <kbd><esc></kbd>       | -             | Quit the plugin             |
| <kbd><c-u></kbd>       | <kbd>↑</kbd>  | Move up                     |
| <kbd><c-e></kbd>       | <kbd>↓</kbd>  | Move down                   |
| <kbd><tab></kbd>       | -             | Multi select and move down  |
| <kbd><shift-tab></kbd> | -             | Multi select and move up    |
| <kbd><enter></kbd>     | -             | Return yazi and go to files |
