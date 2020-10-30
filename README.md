# RTTL player

> Open this page at [https://pelikhan.github.io/arcade-rttl/](https://pelikhan.github.io/arcade-rttl/)

This Arcade extension lets you convert RTTL tunes into MakeCode Arcade
melodies.

You will find a new ``convert RTTL to melody`` block under Music > Melody.

```blocks
let demo = "HauntHouse: d=4,o=5,b=108: 2a4, 2e, 2d#, 2b4, 2a4, 2c, 2d, 2a#4, 2e., e, 1f4, 1a4, 1d#, 2e., d, 2c., b4, 1a4, 1p, 2a4, 2e, 2d#, 2b4, 2a4, 2c, 2d, 2a#4, 2e., e, 1f4, 1a4, 1d#, 2e., d, 2c., b4, 1a4"
let melody = music.convertRTTLToMelody(demo)
music.playMelody(melody, 120)
```

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/pelikhan/arcade-rttl** and import

## Edit this project ![Build status badge](https://github.com/pelikhan/arcade-rttl/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/pelikhan/arcade-rttl** and click import

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>