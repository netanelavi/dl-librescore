# dl-musescore

<img src="images/logo.png" width="256" alt="LibreScore logo">

[![Discord](https://img.shields.io/discord/774491656643674122?color=5865F2&label=&labelColor=555555&logo=discord&logoColor=FFFFFF)](https://discord.gg/DKu7cUZ4XQ) [![Github All Releases](https://img.shields.io/github/downloads/LibreScore/app-librescore/total.svg?label=App)](https://github.com/LibreScore/app-librescore/releases/latest) [![Github All Releases](https://img.shields.io/github/downloads/LibreScore/dl-musescore/total.svg?label=Browser+extension)](https://github.com/LibreScore/dl-musescore/releases/latest) [![npm](https://img.shields.io/npm/dt/musescore-dl?label=Command-line+tool)](https://www.npmjs.com/package/musescore-dl)

Download sheet music from MuseScore

> DISCLAIMER: This is not an officially supported MuseScore product

## Installation

There are 3 different installable programs:

| Program           | MSCZ | MIDI | PDF | MP3 | Conversion |     | Windows | macOS | Linux | Android | iOS |
| ----------------- | ---- | ---- | --- | --- | ---------- | --- | ------- | ----- | ----- | ------- | --- |
| App               | ✔️   | ✔️   | ❌  | ✔️  | WIP         |     | ✔️      | ✔️    | WIP   | ✔️      | ❌  |
| Browser extension | ❌   | ✔️   | ✔️  | ✔️  | ❌         |     | ✔️      | ✔️    | ✔️    | ✔️      | ❌  |
| Command-line tool | ❌   | ✔️   | ✔️  | ✔️  | ✔️         |     | ✔️      | ✔️    | ✔️    | ✔️      | ❌  |

> Note: `Conversion` refers to the ability to convert MSCZ files into any other file type, including those not downloadable in the program.
> You can alternatively convert MSCZ files into any other file type using the Webmscore website: https://librescore.github.io

### App

1. Go to the [Releases](https://github.com/LibreScore/app-librescore/releases/latest) page of the `app-librescore` repository
2. Download the latest version for your device
3. Follow the installation instructions for your device to install it

### Browser extension

1. Install [Tampermonkey](https://www.tampermonkey.net)
> Note: If you already installed an old version of the script called "musescore-downloader", please uninstall it from the Tampermonkey dashboard
2. Go to the latest [dl-musescore.user.js](https://github.com/LibreScore/dl-musescore/releases/latest/download/dl-musescore.user.js) file
3. Press the Install button

### Command-line tool

1. Install [Node.js LTS](https://nodejs.org)
2. Open a terminal (do _not_ open the Node.js application)
3. Type `npx musescore-dl`, then press `Enter ↵`

## Building

1. Install [Node.js LTS](https://nodejs.org)
2. `npm install` to install packages
3. `npm run build` to build

- Install `./dist/main.user.js` with Tampermonkey
- `node ./dist/cli.js` to run command-line tool
