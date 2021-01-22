# kieskringen

generating png:
```bash
$ npm install pug-cli
$ ./node_modules/.bin/pug -P < Nederland_kieskringen.svg.pug > Nederland_kieskringen.svg
$ magick convert -crop 550x630+0+0 Nederland_kieskringen.svg Nederland_kieskringen.png
```
