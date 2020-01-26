# Nativefier-apps

Webapps you can turn into apps which I've modified to look more adapted to macOS. As I don't think I'm legally allowed to redistrubute the software, so here's a guide how you can compile one your self.

https://github.com/jiahaog/nativefier

## Requirements / Tested on
- macOS 10.14+
- node + npm
- imagemagick

### Installation of Nativefier
```bash
brew install imagemagick node
npm install nativefier -g
```

## ClickUp
![screenshot](https://gitlab.com/renegadevi/nativefier-apps/raw/master/ClickUp/screenshot.png)
```bash
cd ClickUp
nativefier --name "ClickUp" --icon icon.icns --width 1280 --height 800 --min-height 500 --min-width 800 --inject style.css --title-bar-style 'hiddenInset' --verbose --darwin-dark-mode-support "https://app.clickup.com"
 ```
