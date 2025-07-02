# skim.yazi

[skim](https://github.com/skim-rs/skim) plugin for [Yazi](https://github.com/sxyazi/yazi).

## Dependencies

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

| Key binding   | Alternate key | Action                      |
|---------------|---------------|-----------------------------|
| `<esc>`       | -             | Quit the plugin             |
| `<c-u>`       | <kbd>↑</kbd>  | Move up                     |
| `<c-e>`       | <kbd>↓</kbd>  | Move down                   |
| `<tab>`       | -             | Multi select and move down  |
| `<shift-tab>` | -             | Multi select and move up    |
| `<enter>`     | -             | Return yazi and go to files |

## License

This plugin is MIT-licensed. For more information check the [LICENSE](LICENSE) file.
