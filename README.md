# spritemate
spritemate is a browser based sprite editor for the Commodore 64. This is a very early version of the spritemate tool and is not functional yet. Feel free to download the dist and play around with it, but there's really not much to see yet.

You can check out a version from 2017-09-08: http://spritemate.com/170908/

![spritemate](https://user-images.githubusercontent.com/434355/29740898-0212147a-8a62-11e7-879f-f938bd009718.png)
Screenshot of the first commit

## What it currently does

* choose one of 16 C64 colors from the color palette
* draw pixels on a 24x21 pixel (hires) or 12x21 pixel (multicolor) canvas
* delete pixels
* fill
* shift left, right, up, down
* flip horizontal, vertical
* check your sprite in the preview window
* multicolor and hires mode support
* grid mode on/off in editor
* multiple sprites
* double width & height sprites
* sprite sorting
* undo
* window based GUI

## What it does not yet

* loading & saving as image (PNG), internal format, native C64 binary, SpritePad SPR
* pixel tools like: rotate, copy & paste
* save window layout
* C64 mode restrictions (number of colors per sprite, global sprite colors)
* animation
* stacked sprite layers (onion skinning)
* and tons of other stuff

## History

2017-09-07
* Zoom levels for editor, preview and list view can be set in the config
* Sprites in list view are sortable correctly when size is changing
* Info button has a new modal with version info and links
* sprite streching for preview window

2017-09-06
* Sorting in list view finally works

2017-09-04
* Undo implemented



If you're interested to contribute let me know - happy to team up!
