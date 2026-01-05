<style>
    .hint {
        font-size: 0.67em;
    }
    #game {
        font-size: 0.9rem;
    }
</style>
<script src="/js/funtimes-v1.js"></script>

This is a **batch file text adventure game** I wrote when I was 16, running on the web using a Python library I wrote called [batchfile.py](https://github.com/tassaron/batchfile.py). Batch files are the Windows command prompt equivalent to a Unix shell script, so basically a text file with a list of commands for the terminal to run automatically. Below the game content is a link to the batch file you are currently viewing.

The original game saved your progress into a text file, but here I have redirected the output into a browser cookie. In fact, the entire callstack of the game is stored in that cookie so it can be restored without any server-side state.

<pre><img src="/img/cmdexe.png">
<div id="game">Game is loading...</div></pre>

<input id="user_input" type="text" name="user_input" autocapitalize="off"><input id="submit" type="submit"
        onclick="update()" value="&ldca;&nbsp;Enter"><input id="quit" type="button" onclick="quit()" value="Quit">

<p style="padding-top: 1em;" class="hint" id="hint"></p>
<small>

### How to cheat in FUNTIMES

- **Start with $500:** use `Harry` as your first name and `Potter` as your last name
- **Enter secret invisible debug menu:** in the bedroom, type `debug` and press enter, then `grace` and press enter, then `hopper` and press enter. If you see the text "`bedroom.bat`" below the game window change into "`debug.bat`", that means you were successful.
- **Change any character stat:** in the debug menu, type `weet`, `money`, `str`, `int`, `cha`, or `dex` and press enter to choose which value to increase, then type a number and press enter.
- **Fight unfinished enemies:** in the debug menu, type `lion` or `clone`.
- **Teleport to unfinished area:** in the debug menu, type `cyard` to teleport to the construction yard. Here you can fight a worker to get the wrench for fixing the slushie machine. The wrench is a finished item you can use anywhere.

</small>
