# Keyboard Enhancements for Mac

Add custom key mappings and shortcuts to do things faster and easier in Mac.

Read [A Modern Space Cadet](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/#controlescape) from Steve Losh for enlightenment.

## Mappings

- `Fn` to `Hyper` when in combination with a letter/number/symbol.
- `Option_R` to `Fn`.
- `Shift_R` to `ESC` when typed only.
- `Option + h/j/k/l` to left/down/up/right.

## Ubiquitous Vim Bindings for Normal Mode

- Type `Command_R` to toggle Vim bindings for normal mode.
- Alternatively, type `ESC` to turn off normal mode.

Mappings can be used in normal mode:

![kr4mb vim](screenshots/KR4MB_Vim.png)

## Shortcuts

### Trackpad

Press `Fn`, and single tap different area of trackpad to move windows around.

![btt trackpad](screenshots/BTT_Trackpad_1.png)

### Tab Mode

Press `Tab + h/l` to switch app like `Command + Shift + Tab` or `Command + Tab`.

### In Finder

- `F2` to rename
- `Forward Delete` to `Command_L + Delete`
- `Command + N` to create new folder

### Switch/Open Apps

Press `Fn + letter` to open the app or switch to it.

- `Fn + D`: Show Desktop
- `Fn + V`: MacVim
- `Fn + F`: Firefox Aurora
- `Fn + C`: Chrome
- `Fn + G`: GitHub
- `Fn + W`: Wunderlist
- `Fn + E`: Calendar
- `Fn + I`: iTerm

## Tools (free)

- [KeyRemap4MacBook](https://pqrs.org/macosx/keyremap4macbook/index.html.en)
- [BetterTouchTool](http://www.boastr.de/)

## Setup

### KeyRemap4MacBook

Import settings from Terminal:

```bash
$ sh ./kr4mb_settings.sh
```

To Export your Setting:

```bash
$ /Applications/KeyRemap4MacBook.app/Contents/Applications/KeyRemap4MacBook_cli.app/Contents/MacOS/KeyRemap4MacBook_cli export > ./kr4mb_settings.sh
```

### BetterTouchTool

Import `BetterTouchTool.settings` in BetterTouchTool.
