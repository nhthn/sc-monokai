![Screenshot](screenshot.png)

Tired of staring at a white screen in a dark performance venue? You're in luck! The famous [Monokai](http://www.monokai.nl/blog/2006/07/15/textmate-color-theme/) TextMate theme is now available for SuperCollider IDE at the low price of $0.

There is a catch, however: installation is a little tricky.

`sc_ide_conf.yaml` is for the editor. There is no easy way to install this; it has to be manually grafted into `Platform.userConfigDir +/+ "sc_ide_conf.yaml"`. It goes under IDE/editor.

`custom.css` is for the help files. It goes in `~/.local/share/SuperCollider/Help`. Sorry, I don't know what that is for OS X and Windows.