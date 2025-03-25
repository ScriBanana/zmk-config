# An easy-to-learn, Optimot-based Corne layout

## Dependencies:
- _Layout: [Optimot](https://optimot.fr/) (choose Optimot ISO driver)_
- _Keyboard: [Corne](https://github.com/foostan/crkbd)_
- _Firmware: [ZMK](https://zmk.dev/)_

## Keymap:
![VisualKeyMap](/Illustrations/CorneOptimot.webp)

## Features:
#### Leverages Optimot and its driver
- The Optimot layout is highly optimised for French and English secondarily
- It gives pride of place to alternating hands, rolling and avoiding collisions (see the [documentation](https://optimot.fr/notes-conception.html))
- Its driver provides with numerous ideally placed characters in secondary layers
- `AltGr` is in a key position to access them
#### Easy to learn, easy to swap
- Few layers
- Utility keys don't change between layers
- Close to a standard keyboard (_learn your layout only once_):
	- Familiar numbers and symbols layouts
	- Usual navigation shortcuts, yet more accessible
 	- No dedicated key, homerow mod nor comboes
#### Mouse-friendly (right-handed)
- Utility modifiers heavily clustered on the left hand
- Mouse-support layer on the left hand (one hand) for natively two-handed shortcuts (`ctrl+C`, `ctrl+V`, etc)
#### Painless shortcuts
- Typing modifiers under the thumbs (`SymNum`, `Shift` and `AltGr`)
- Modifiers and layer switchers are easily comboed with fat thumbs
- Navigation and deletion are combinable with `ctrl`, `shift` and `GUI`

## Limitations:
- `AltGr+Space` (non-breaking space) is not really possible, thus the dedicated key in the symbol layer.
- `Caps-word` doesn't stop with some punctuation characters (ZMK limitation due to the optimot layer).
- `Shift+Alt+Tab` is not really possible (`Shift+Alt`, in general).
- Browser navigation (`Alt+left/right`) is two-handed, but any mouse with five buttons or more will provide with it for the right hand.

## Notes:
- Made for Linux; Windows should work; MacOS would require light changes.
- What is loaded as firmware (`.keymap` file) differs from the picture, as Optimot drivers modifies the QWERTY layout downstream.
- The gaming layer is entirely optional.
- `Alt` and `GUI` may be swapped depending on one's use.
