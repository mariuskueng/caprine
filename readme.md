# <img src="media/Icon.png" width="45" align="left">&nbsp;parrot

> Unofficial WhatsApp Mac OS Client

*Requires OS X 10.8+ or Linux. Windows support planned.*

## Install

[**Download**](https://github.com/mariuskueng/parrot/releases/latest), unzip, and move `parrot.app` to the `/Applications` directory.


## Compact mode

The interface adapts when resized to a small size.

## Desktop notifications

Desktop notifications can be turned on in Preferences.

NOTE: There is a [known bug](https://github.com/atom/electron/issues/2294) with Electron's handling of desktop notifications on systems running Gnome 3 that may cause Parrot to crash if notifications are clicked. Until this bug is resolved, do not click on notifications if they cause the app to crash on your system.

## Dev

Built with [Electron](http://electron.atom.io).

###### Commands

- Init: `$ npm install`
- Run: `$ npm start`
- Build OS X: `$ npm run build-osx`
- Build all: `$ npm run build` *(OS X only)*


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
