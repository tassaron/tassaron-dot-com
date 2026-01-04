<style>
    #game {
        border: 8px dashed #4e315e;
        width: 800px;
        height: 600px;
        margin: auto;
        margin-top: 1rem;
        margin-bottom: 1rem;
        box-shadow: 0 0 0.75rem 0.375rem rgba(78, 49, 94, 0.3);
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

## How to play

- Water starts flowing when the countdown reaches zero.
- End the level by guiding water to the side of the grid indicated by the arrow.
- You get more points if the game is in fast-forward speed.
- You get bonus points if water goes through the same pipe twice.

</div>
<div id="game"></div>
<div id="game_controls">
<button type="button" id="pause_button">Pause</button><br>

[source code on github](https://github.com/tassaron/pipe-puzzle)

### Graphics attribution

- `explosion.png` created by [Sogomn](https://opengameart.org/content/explosion-3)
- `pipes.png` is originally by [TwistedDonkey](https://opengameart.org/content/2d-pipe-parts), edited by tassaron

</div>
<script src="/js/pipe-puzzle-v1.js"></script>
