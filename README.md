# ondersteuningsverklaringen

This repo uses a map of Dutch electoral regions ('kieskringen')
to overlay with info about numbers of support declarations ('ondersteuningsverklaringen')
obtained in said region.
Obtaining such support is something every new political party
needs to initially go through in the Netherlands in order to be deemed electable.

## usage

generating png:
```bash
$ npm install pug-cli
$ ./node_modules/.bin/pug -P < Nederland_kieskringen.svg.pug > Nederland_kieskringen.svg
$ magick convert -crop 550x630+0+0 Nederland_kieskringen.svg Nederland_kieskringen.png
```
