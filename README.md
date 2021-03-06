# thomas [![Build Status][travis-image]][travis-url]

> Simple pomodoro timer

![](media/screenshot.png)

## Install

```sh
git clone https://github.com/andrepolischuk/thomas
cd thomas
npm install
```

If you use Ubuntu or Debian, you also may need to install `nodejs-legacy` that creates `node` symlink.

```sh
sudo apt-get install nodejs-legacy
```

## Shortcuts

* `CommandOrControl+Alt+T` — show application *(global)*
* `Escape` — hide application
* `CommandOrControl+Enter` — start/cancel timer

## Run

```sh
npm start
```

## Build

Build the application for specified platform:

```sh
npm run build:macos
npm run build:linux
npm run build:windows
```

## License

MIT

[travis-url]: https://travis-ci.org/andrepolischuk/thomas
[travis-image]: https://travis-ci.org/andrepolischuk/thomas.svg?branch=master
