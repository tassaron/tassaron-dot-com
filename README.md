# tassaron dot com

This is the "source code" for [my website](http://tassaron.com)

It gets transformed into HTML by **[muffin-mash](https://github.com/tassaron/muffin-mash)**

## development

- run `python -m venv env` to make a Python virtualenv
- run `./env/bin/pip install git+https://github.com/tassaron/muffin-mash` to install mash
- run `npm i` to install `nodemon` and `concurrently`
- run `npm start`
- **(optional, to test Funtimes)** run `bat2web.py` to run Flask app that serves `/game/funtimes/api` (must disable CORS and modify API url in `funtimes-v1.js` file; it's tedious)

## bundles

`/pages/js` contains various bundled JavaScript files created from source code contained in their own repos. These bundles are included for convenience and redundancy/preservation. They should not be gazed upon by mortal eyes (read the actual source code instead, linked below).

- `jezzball-v1.js`: [jezzball-transgender](https://github.com/tassaron/jezzball-transgender)
- `breakout-v1.js` - [breakout](https://github.com/tassaron/breakout)
- `pipe-puzzle-v1.js` - [pipe-puzzle](https://github.com/tassaron/pipe-puzzle) + [muffin-game](https://github.com/tassaron/muffin-game)
- `rodents-revenge-v1.js`: [rodents-revenge](https://github.com/tassaron/rodents-revenge)
- `speed-limit-v1.js`: [speed-limit](https://github.com/tassaron/speed-limit)
- `funtimes-v1.js`: [bat2web](https://github.com/tassaron/bat2web)

`/pages/download` contains more of such files:

- `food-prefs-v1.0-alpha.js` - [openrct2-food-prefs-plugin](https://github.com/tassaron/openrct2-food-prefs-plugin)
