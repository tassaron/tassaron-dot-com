# tassaron dot com

This is the "source code" for [my website](http://tassaron.com)

It gets transformed into HTML by **[muffin-mash](https://github.com/tassaron/muffin-mash)**

## development

- run `python -m venv env` to make a Python virtualenv
- run `./env/bin/pip install git+https://github.com/tassaron/muffin-mash` to install mash
- run `npm i` to install `nodemon` and `concurrently`
- run `npm start`

## bundles

`/pages/js` contains various bundled JavaScript files created from source code contained in their own repos. These bundles are included for convenience and redundancy/preservation. They should not be gazed upon by mortal eyes (read the actual source code instead, linked below).

- `jezzball-v1.js`: [jezzball-transgender](https://github.com/tassaron/jezzball-transgender)
- `breakout-v1.js` - [breakout](https://github.com/tassaron/breakout)
- `pipe-puzzle-v1.js` - [pipe-puzzle](https://github.com/tassaron/pipe-puzzle) + [muffin-game](https://github.com/tassaron/muffin-game)
- `rodents-revenge-v1.js`: [rodents-revenge](https://github.com/tassaron/rodents-revenge)
