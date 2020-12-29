# tile-bleed-margin-generator

Automatically stretch out the 1px edge of each tile in a sprite sheet to compensate for tile bleed in 2D game development.

## bleed.sh

first argument is the name of the spritesheet we want to bleed.
second argument is `SPRITESHEET_WIDTH`
third argument is `SPRITESHEET_HEIGHT`
fourth argument is `TILE_SIZE`

Example
`sh bleed.sh spritesheet.png 640 576 16`

## How to use in Unity

![Unity tilemap settings](https://github.com/johnedvard/tile-bleed-margin-generator/blob/master/Unity-tilemap-settings.png?raw=true)
