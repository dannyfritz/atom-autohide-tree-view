# autohide-tree-view package

Hide the tree view, show it on hover.

![Image inserted by Atom editor package auto-host-markdown-image](https://raw.githubusercontent.com/olmokramer/atom-autohide-tree-view/master/images/screencast.gif)

## Config

| setting | type | unit | default | description |
|---|---|---|---|---|
| `animate` | boolean | none | true | Enable/disable the animation when showing the menu |
| `showDelay` | number | s (seconds) | 0.2 | The delay before the tree view will show when hovered |
| `hideDelay` | number | s (seconds) | 0.2 | The delay before the tree view will hide when hovered |
| `hiddenWidth` | integer | px (pixels) | 1 | The width of the hidden tree view |
| `pushEditor` | boolean | none | false | Push the editor when showing the tree view |

## Commands

| command | scope-selector:keybinding | description |
|---|---|---|
| `autohide-tree-view:enable` | none | Enable autohide |
| `autohide-tree-view:disable` | none | Disable autohide |
| `autohide-tree-view:toggle-enabled` | none | Enable/Disable autohide |
| `autohide-tree-view:show` | none | Show tree view |
| `autohide-tree-view:hide` | none | Hide tree view |
| `autohide-tree-view:toggle-visible` | `atom-workspace`: <kbd>Ctrl-\\</kbd> or <kbd>Cmd-\\</kbd> | Show/Hide tree view |

## Issues/suggestions

Please file issues or suggestions on the [issues page on github](https://github.com/olmokramer/autohide-tree-view/issues/new), or even better, [submit a pull request](https://github.com/olmokramer/atom-autohide-tree-view/pulls)

## License

`autohide-tree-view` is released under the [MIT License](LICENSE.md)<br>
&copy; 2015 Olmo Kramer