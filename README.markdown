# Keyboard Enhancements for Mac

Add custom key mappings and shortcuts to do things faster and easier in Mac.

Please read [A Modern Space Cadet / Steve Losh](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/#controlescape) for enlightenment.

## Tools

- [KeyRemap4MacBook](https://pqrs.org/macosx/keyremap4macbook/index.html.en)
- [BetterTouchTool](http://www.boastr.de/)

## Mappings

![kr4mb 1](screenshots/KR4MB_1.png)
![kr4mb 2](screenshots/KR4MB_2.png)

### Ubiquitous Vim Bindings for Normal Mode

Type `Command_R` to toggle Vim bindings for normal model.
Alternatively, type `ESC` to turn off normal model.

![kr4mb vim](screenshots/KR4MB_Vim.png)

## Shortcuts

### Trackpad

Press `Fn`, single tap different corner of trackpad to move windows around.

![btt trackpad](screenshots/BTT_Trackpad.png)

### Keyboard

Press `Fn + app' char` to open the app or switch to it.

![btt keyboard](screenshots/BTT_Keyboard.png)

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
