<style>
    #game {
        border: 8px dashed #4e315e;
        box-shadow: 0 0 0.75rem 0.375rem rgba(78, 49, 94, 0.3);
        width: 640px;
        height: 598px;
        margin: auto;
        margin-top: 1rem;
        margin-bottom: 1rem;
        position: relative;
        display: block;
    }

    #pause_button {
        padding: 1rem 2rem;
        border-radius: 0;
    }

    #pause_button:focus-within, #pause_button:hover {
        box-shadow: 0 0.375rem 0.5rem rgba(78, 49, 94, 0.4);
        outline: rgba(78, 49, 94, 0.4) solid 0.375rem;
    }

    #game_controls {
        text-align: center;
    }
</style>
<div id="help_text">
    Pass cars ahead of you in your lane to collect their coins. Copper, silver, and gold coins are worth $500, $1000, and $1500 respectively. Coins will also spawn randomly on the opposite lane of the road, along with jerrycans you can collect to refuel your vehicle. Watch that fuel meter!! And don't crash into too many traffic cones either. There's a lot of crazy drivers out there... but at least you're following the speed limit! 🤷‍♀️<br><br>
    Playable with a keyboard, mouse, or touchscreen
</div>
<div id="game"></div>

<div id="game_controls">
<button type="button" id="pause_button">Pause</button><br>

[source code on github](https://github.com/tassaron/speed-limit)

### Graphics Attribution

- `cars.png` is created by [PixelShack](https://opengameart.org/content/small-city-cars)
- `mycars.png` is a version of `cars.png` edited by tassaron to create additional sprites
- `grass.png` is created by [gfx0](https://opengameart.org/content/32x32-tilemap-grass-dungeon-floors-snow-water)
- `explosion.png` is created by [Sogomn](https://opengameart.org/content/explosion-3)
- `coin.png` is created by [Clint Bellanger](https://opengameart.org/content/animated-coins) for Liberated Pixel Art

</div>
<script src="/js/speed-limit-v1.js"></script>
