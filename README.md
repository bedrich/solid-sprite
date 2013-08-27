Solid Sprite
============

Creating sprites like a boss.

## Installation

1. First things first, install [Homebrew](http://brew.sh/).

2. Install [ImageMagick](http://www.imagemagick.org/script/index.php):

        brew install imagemagick

3. Install [Ghostscript](http://www.ghostscript.com/).

        brew install ghostscript

4. Clone this repo:

        git clone git@github.com:bedrich/solid-sprite.git solid-sprite

## Usage

From within the directory where you installed `solid-sprite`:

    ./bin/solidsprite [images_directory] [sprite_filename]

Options

- `-g` Grid value, e.g. `30`
- `-v` Will glue images vertically rather than horizontally
- `-t` Will remove transparent pixels from images before making sprite (caution: this will modify the original images).
- `--debug` Will append labels to the sprite with position and size information. This will also force the sprite to be vertical.
