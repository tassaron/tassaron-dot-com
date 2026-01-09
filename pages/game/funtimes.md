<style>
    .hint {
        font-size: 0.67em;
    }
    .console {
        font-size: 0.9rem;
        min-height: 280px;
        overflow: scroll !important;
        background-color: rgba(0,0,0,0.1);
        width: 72ch;
        min-width: 661px;
        border-style: solid;
        border-color: lightgray;
        border-width: 4px;
        margin-top: 8px;
    }
    @media (max-width: 500px) {
        .console {
            width: 100%;
            min-width: 72ch;
        }
    }
    input {
        height: 2rem;
        padding: 0;
        border: 4px solid lightgray;
        margin: 0 0.5rem;
    }
    input[type=button], input[type=submit] {
        height: 2.67rem;
        min-width: 8ch;
    }
</style>
<script src="/js/funtimes-v1.js"></script>

This is a **batch file text adventure game** I wrote when I was 16, running on the web using a Python library I wrote called [batchfile.py](https://github.com/tassaron/batchfile.py). Batch files are the Windows command prompt equivalent to a Unix shell script, so basically a text file with a list of commands for the terminal to run automatically. Below the game content is a link to the batch file you are currently viewing.

The original game saved your progress into a text file, but here I have redirected the output into a browser cookie. In fact, the entire callstack of the game is stored in that cookie so it can be restored without any server-side state.

<pre><img style="width: 669px; max-width: 72ch; position:absolute; overflow-x: hidden;" alt="C:\WINDOWS\System32\cmd.exe" src="/img/cmdexe.png">
<div id="game" class="console">Game is loading...</div></pre>

<input id="user_input" style="margin-left: 0; width: 36ch;" type="text" name="user_input" autocapitalize="off"><input id="submit" type="submit"
        onclick="update()" value="&ldca;&nbsp;Enter"><input id="quit" type="button" onclick="quit()" value="Quit">

<p style="padding-top: 1em;" class="hint" id="hint"></p>

## Original Readme.txt from 2010

<pre class="console">
A simple little life sim composed of a million batch files written just to waste some time at school

FUNTIMES is a text-adventure game where you assume the role of a teenager living the longest day ever. During this day you'll have to do many tasks to gain weet points. These weet points are a representation of how "weet" you are -- weetness being the ultimate measure of one's awesomeness. You get weet points by doing weet things like finding a girlfriend, posting on forums, helping people out, etc. -- just be awesome and the game will do the rest of the work.
</pre>

### How to cheat in FUNTIMES

<small>

- **Start with $500:** use `Harry` as your first name and `Potter` as your last name
- **Enter secret invisible debug menu:** in the bedroom, type `debug` and press enter, then `grace` and press enter, then `hopper` and press enter. If you see the text "`bedroom.bat`" below the game window change into "`debug.bat`", that means you were successful.
- **Change any character stat:** in the debug menu, type `weet`, `money`, `str`, `int`, `cha`, or `dex` and press enter to choose which value to increase, then type a number and press enter.
- **Fight unfinished enemies:** in the debug menu, type `lion` or `clone`.
- **Teleport to unfinished area:** in the debug menu, type `cyard` to teleport to the construction yard. Here you can fight a worker to get the wrench for fixing the slushie machine. The wrench is a finished item you can use anywhere.

</small>
