 


> Open this page at [https://kevmcdonk.github.io/learnpixelart_thegame/](https://kevmcdonk.github.io/learnpixelart_thegame/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/kevmcdonk/learnpixelart_thegame** and import

## Edit this project ![Build status badge](https://github.com/kevmcdonk/learnpixelart_thegame/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/kevmcdonk/learnpixelart_thegame** and click import

## Importing png files
To import png files as assets, use [this brilliant tool](https://riknoll.github.io/pxt-arcade-asset-tool/) by [Richard Knoll](https://github.com/riknoll) - you can [read more](https://learn.adafruit.com/next-level-makecode-arcade-games/asset-tool) on this if you want but to use, drag the png into the tool, copy the output and load it into main.ts in "function initializeCoins()" as a new push to the coins array, e.g.

// Thanks to @collin_sparkles for Bunny-Rabbit
    coins.push(img`
    . . . . . . . . . . . . . . . .
    . . . . . . . . . . . . . . . .
    . . . . . . d d 4 4 4 . . . . .
    . . . . . d d 4 4 4 4 . . . . .
    . . . . d 4 4 . 4 . 4 . 4 . . .
    . . . d . . 4 4 f 4 4 . . . . .
    . . d . . . 4 4 4 4 . . . . 4 .
    . . d . . . . 4 4 . . . . . 4 .
    . d 4 . . d 4 4 4 4 4 . . . . 4
    . 4 4 . d 4 . 4 4 4 . 4 . . . 4
    4 4 . . d 4 4 4 4 4 4 4 . . . 4
    d 4 . . . 4 . 4 4 4 . . . . . .
    . 4 . . 4 4 4 . 4 . 4 4 . . . .
    . . f f f f f f f f f f f f . .
    . f c c c c c c c c c c c f f .
    . f c f f f f f f f f f c f f . 
    `);

Not that you should include who the pixel art was from as credit


## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/kevmcdonk/learnpixelart_thegame/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
