A plugin to give guests a preference for some food stalls over others.

<div style="float:right">

![screenshot of window added by plugin showing information about guest food preferences](/img/ogfp/screenshot.png)

</div>

## [Watch my video about this project 🎥](https://youtu.be/v_YjGfs00F0)

## [Download v1.0-alpha (right-click and save as)](/download/food-prefs-v1.0-alpha.js)

## [View source code on GitHub](https://github.com/tassaron/openrct2-food-prefs-plugin)

## How it works

When loading a map, this plugin looks at what food/drinks are available to the player (either currently or in future due to research). All guests will be **assigned a food preference that is possible to satisfy** within the loaded scenario. The idea is to incentivize researching more than one type of food/drink stall.

At the **beginning of each in-game day**, each food/drink stall **lures guests for 3 seconds** (120 game ticks), setting and resetting their hunger/thirst appropriately so the guest will buy (assuming the item is not too expensive for them). This only works on the tile directly in front of a stall, and ignores guests who are unhappy or already have a food or drink item.

### Known issues

- If you load new stalls into a map using the object selection window, you must save and reload the map before guests will be generated with a preference for the newly-loaded objects. (This refers to food stalls that are not normally obtainable even via research.) (This is probably fixable but not worth the effort?)
- Occasionally guests get stuck on the corner of a stall and thus don't buy anything, but they'll be safely freed and reset to normal once the luring period ends.
- This probably doesn't work in multiplayer. I haven't tested that yet.

## Thanks

Thanks to the entire [OpenRCT2](https://github.com/OpenRCT2/OpenRCT2) team and community for keeping this classic game alive. Thanks to [Basssiiie](https://github.com/Basssiiie) for creating [OpenRCT2-Simple-Typescript-Template](https://github.com/Basssiiie/OpenRCT2-Simple-Typescript-Template) and [OpenRCT2-FlexUI](https://github.com/Basssiiie/OpenRCT2-FlexUI). Thanks also to [Manticore-007](https://github.com/Manticore-007) for the Peep Editor plugin, which taught me that Duktape can print stacktraces.

## Anti-Thanks

No thanks to the tech industry that injures my love of software every day with its continual invention of problems in search of a solution. Screw your hype bubbles.
