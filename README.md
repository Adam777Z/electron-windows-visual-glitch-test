# Electron Windows visual glitch test

A minimal Electron application to test window visual glitch on Windows.

Issue: [Maximize window visual glitch on Windows](https://github.com/electron/electron/issues/35246)\
Fixed in [Electron v38.0.0](https://github.com/electron/electron/releases/tag/v38.0.0)

Based on [electron-quick-start](https://github.com/electron/electron-quick-start)

### Download
Download the latest version on the [Releases](https://github.com/Adam777Z/electron-windows-visual-glitch-test/releases/latest) page.

### App data location
[See here](https://www.electronjs.org/docs/latest/api/app/#appgetpathname).

#### Portable mode (Windows only)
Supports storing the app data in the `data` folder next to the executable file.\
To enable, create the `data` folder where the executable file is located.\
The `data` folder already exists in the Portable version ZIP file.

### How to build
1. npm install
2. npm run make