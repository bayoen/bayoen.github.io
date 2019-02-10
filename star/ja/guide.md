---
layout: bayoen-star-ja
---

# Guide

Let us give you instructions for **bayoen-star**. If you are in hurry, check 'Summary,' or look at 'More Details!'

<div class="toc">
    <h2>Content</h2>
    <ul>
        <li><a href="#Summary">Summary</a></li>
        <li><a href="#Details">More Details</a></li>
    </ul>
</div>

----

<a name="Summary"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Summary

Using **bayoen-star** is such a piece of cake! To do everything you want, just press few buttons! (from developers)

1. Run both **bayoen-star** and **Puyo Puyo Tetris**. (any order)
2. Play games in **Puyo Puyo Tetris** with any setting, any type
3. Check out the **bayoen-star** getting scores
4. Profit!

And also, there is [**demo video**](https://www.youtube.com/playlist?list=PLK_vOCD9v3gUABMGU1R_VNhv5_s-LctnE)!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <br/><span>A mainwindow of <strong>bayoen-star</strong> is following:</span>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-main-en.png" class="box" alt="bayoen-star-initial"/>
    <br/><span>It's so intuitive for everybody (also from developers)</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <br/><span>In <strong>Menu</strong>, you can reset all scores; or set goal; or change settings and the mode of scoreboard!</span>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-menu-selected-en.png" class="box" alt="bayoen-star-instuction-menu-selected"/>
        <br/><span>You'd better set a goal for friendly match or game league like <strong>'First to #15' match</strong></span>
        <br/><span>Use <strong>Overlay</strong> to float scoreboard over the game window!</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <span><strong>bayoen-star</strong>'s scoreboard show us such things!</span>    
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-and-crown-en.png" class="box" alt="bayoen-star-and-crown"/>
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-mode-selected.png" class="box" alt="bayoen-star-menu-mode-selected"/>
    <br/><span>You can change scoreboard mode to display types of score you want</span>
    <br/><span>Feel free for checking out other functions!</span>
    <br/><span>You should close <strong>bayoen-star</strong> directly in tray icon</span>
</p>


<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-9.png" class="shadow-box" alt="bayoen-star-example-ingame-league-1"/>
    <br/><span>And also, in puzzle league....</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-10.png" class="shadow-box" alt="bayoen-star-example-ingame-league-2"/>
    <br/><span>you can enjoy whole matches XD</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <span><strong>THE END!</strong></span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
   <img src="{{ site.lang_url }}/res/tumblr_inline_pev40xy80F1rg6qfd_1280.png" class="box" width="30%" alt="bayoen~"/>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Details"> </a>
<a name="Functions"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## More Details

Shall we be more specific? We listed all functions of **bayoen-star**. Please check one by one!

<div class="toc-sub">
    <h2>Detail Content</h2>
    <ul>
        <li><a href="#Main">Main Window</a>
            <ul>
                <li><a href="#Components">Conponents</a></li>
                <li><a href="#Symbol">Symbols</a></li>
            </ul>
        </li>
        <li><a href="#Function"><strong>bayoen-star</strong> Functions</a></li>
        <li><a href="#Menu">Menu</a>
            <ul>
                <li>Reset</li>
                <li><a href="#Goal">Goal</a></li>
                <li><a href="#Overlay">Overlay</a></li>
                <li><a href="#Settings">Settings</a></li>
                <li><a href="#Mode">Mode</a></li>
            </ul>
        </li>
        <li><a href="#Troubleshooting">Trouble Shooting</a>
            <ul>
                <li><strong>bayoen-star</strong> All Reset</li>
            </ul>
        </li>        
    </ul>
</div>

----

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Main"> </a>
<a name="Components"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### Main Window

Here's a instruction of **bayoen-star**'s main window.

#### Components of Main Window

The main window contains this!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-initial.png" class="box" alt="bayoen-star-initial"/>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-main-en.png" class="box" alt="bayoen-star-instuction-main"/>
    <br/><span>Main window of <strong>bayoen-star</strong></span>
</p>

1. Scoreboard: The left and right side of screen indicate player 1 and player 2 respectively. There are three [symbols](#Symbol) and five [modes](#Mode). The interval of all scores between 0 and 9999. otherwise... we are totally sorry.
2. Game Status: Shows the status of **Puyo Puyo Tetris**. There are three things:
    - **Offline**: **Puyo Puyo Tetris** is offline. Turn on **Puyo Puyo Tetris** and play games to turn on the counter.
    - **Ready**: **Puyo Puyo Tetris** is turned-on. **bayoen-star** is ready. Play games to turn on the counter.
    - **Working**: The counter is on! If someone get star or game score, the score be applied in scoreboard.
3. [Menu](#Menu): You can control **bayoen-star** via a menu. For more details, see descriptions below!
4. [Goal](#Goal): It summerizes serial games such as friendly matches and competitions and also notifies who wins and losses. In menu, you can set and reset a goal. For more details, see descriptions below!

Score is tallied for **'Star+'** and **'Crown'** . You can turn it on and off from the menu. For more information, please see the goal settings below!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Symbol"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

#### Symbols of Scoreboard

Here are three symbol on the scoreboard. It's pretty because we extract them from **Puyo Puyo Tetris**!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-and-crown-en.png" class="box" alt="bayoen-star-and-crown"/>
    <br/><span>Three symbols of <strong>bayoen-star</strong></span>
</p>

- Star: Star shape, show current stars in game
- Star+: Star and plus shape, it counts stars
- Crown: Crown shape, it counts games

You can change counted scores in [Menu](#Menu), [Settings](#Settings).

_The scores of **bayoen-star** are imaginary. It doesn't affect real scores or balance of **Puyo Puyo Tetris**!_

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Function"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### **bayoen-star** Functions

- Detect: **bayoen-star** works only when **Puyo Puyo Tetris** is running. If **Puyo Puyo Tetris** is offline, **bayoen-star** sleeps.

- Count: In **Puyo Puyo Tetris** game playing, when someone gets a star, **bayoen-star** refreshes the scoreboard.

- Save: **bayoen-star** save scores and settings in real-time. Even if **bayoen-star** get broken, some information could be recovered.
    - Scores: **data.json** at the path of **bayoen-star**
    - Settings: **pref.json** at the path of **bayoen-star**

 

- Exit: When you close the main window of **bayoen-star**, it is minimized into system tray instead of closing. To exit **bayoen-star** completely, select 'Exit' of the icon of system tray!

- Memory: (important) **bayoen-star** uses memory hooking to counting stars and has two issues:
    - Wouldn't **Puyo Puyo Tetris** slow down?
        - We made **bayoen-star** pretty light. So, if you achieved requirement for running **Puyo Puyo Tetris**, you can even stream it without any delay!
        
        _If it's very slow, please report via <a href="https://github.com/bayoen/bayoen-star-exe/issues" target="_blank"><strong>Issue/Idea</strong></a>!_
    - Is **Puyo Puyo Tetris** safe under memory hacking?
        - **bayoen-star** does not modify any memories, ONLY READS IT.
        - **bayoen-star** reads information which we can directly figure out.
        
        <!-- _Especially, we trace **Steam ID** for identification_ -->

We made **bayoen-star** with safety!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Menu"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### Menu

Here is the menu of **bayoen-star**

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-instuction-menu-selected-en.png" class="box" alt="bayoen-star-instuction-menu-selected"/>
    <br/><span><strong>bayoen-star</strong>'s menu</span>
</p>

1. **Reset Scoreboard**: Reset 'Star+' and 'Crown' and refresh scoreboard.
2. **Ser/Reset Goals**: Set a goal and display its result with counted scores. See ['Goal'](#Goal).
3. **Scoreboard Overlay**: Overlay a new scoreboard with transparent background. See ['Overlay'](#Overlay).
4. **Change Settings**: Change the appearance and scores and set whether or not to export files. See [Settings](#Settings).
5. **Scoreboard Mode**: Change the type of scoreboard. See [Mode](#Mode).

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Goal"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

#### Goal 'Target Score to Win'

Set a goal and display its result with counted scores. You can enable it anytime, it is very useful for friendly match and tournament.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-goal.png" class="box" alt="bayoen-star-menu-goal"/>
    <br/><span>Menu of Goal</span>
</p>

1. **'Set'**: Open 'Set Goal' screen. If a goal setting is done, show the goal above the scoreboard.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-goal-set.png" class="box" alt="bayoen-star-menu-goal-set"/>
    <br/><span>Setting</span>
</p>

- **'Type'**: We present two type of goals
    - **FIRST #**: 'First to **#score**' match! The player who get **#score#** first won.
    - **TOTAL #**: A match with total **#score**! The player who get more scores overall **#score** match.
- **'Counter'**: You can set 'Star+' counter or 'Crown' counter. Possible interval of the goal is from 0 to 9999!

2. **'Remove'**: Remove all goals and hide it from scoreboard.

<p align="center">
    <span>When goal setting is done, it looks like this:</span>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-mode-2-fit.png" class="box" alt="bayoen-star-example-mode-2-fit"/>
    <br/><span><strong>Crown FT10 (First, Crown, 10 Scores)</strong></span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-total-none.png" class="box" alt="bayoen-star-example-goal-total-none"/>
    <br/><span><strong>Star 20 Total (Total, Star+, 20 Scores)</strong></span>    
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Overlay"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

#### Overlay 'Scoreboard over **Puyo Puyo Tetris**'

**bayoen-star** is not able to be overlaid over the game screen... Instead, you can add another scoreboard **overlay** with transparent background!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-overlay-menu.png" class="box" alt="bayoen-star-overlay-menu"/>
    <br/><span><strong>Overlay</strong> Screen and Sub-menu</span>
</p>

**Overlay** is a duplicated scoreboard, and has several functions!

- **Drag Move**: You can mode **Overlay** using mouse drag
- **Change Size**: You can do mouse-wheeling to change the size of **Overlay**
- **Sub-menu**: Left-mouse-click shows pupup menu of **Overlay**
    - **'Fixed'**: Fix **Overlay** on the screen. When fixed, it can not be moved or resized. And it also follows **Puyo Puyo Tetris** window.
    - **'Reset'**: Reset all scores. To avoid misclick, it strictly operates under 'Shift + Click'!
    - **'Close'**: Close **Overlay**

_Overlay we just introduced is not for **Streaming**! If you'd like to use our works in your stream, see [**'Streaming'**]({{ site.lang_url }}/en/streaming.html)!_

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-arcade.png" class="shadow-box" alt="bayoen-star-example-ingame-arcade"/>
    <br/><span>Now we can <strong>Overlay</strong>!</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Settings"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

#### Settings 'Control Panel'

This is setting window of **bayoen-star**. You can change the appearance and scores and set whether or not to export files.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-settings-en.png" class="box" alt="bayoen-star-settings-ko"/>
    <br/><span><strong>Setting</strong> window</span>
</p>

**A. Main Settings**
1. **Top Flag**: If checked, Set **bayoen-star** top most
1. **Auto Hide**: If checked, hide scoreboard when you are not in game (**'Working'** status)
1. **Export Text**: If checked, export score data into text file
1. **Size Adjustment**: If checked, maximize the size of scoreboard
1. **Chroma Key**: Set/clear chroma key color for your internet stream

**B. Score Monitor**
- **'Star+', 'Crown'** Score: You can edit **'Star+'** and **'Crown'**. 'Star' score is read only!
- **'Win Count'**: Required star score to win a single game. It's read only!
- **'Load'** (refresh): Refresh scores of **'Star+'** and **'Crown'** in score monitor.
- **'Save'**: Save current scores of **'Star+'** and **'Crown'**.

_Do you stream **Puyo Puyo Tetris**? so look at [**'Streaming'**]({{ site.lang_url }}/ko/streaming.html) as well!_

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Mode"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

#### Mode 'Displaying Type of Scoreboard'

You can change the type of appearance of the scoreboard. We provide all possible modes of scoreboard.

<p align="center">    
    <img src="{{ site.lang_url }}/res/bayoen-star-and-crown-en.png" class="box" alt="bayoen-star-and-crown"/>
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-mode-selected.png" class="box" alt="bayoen-star-menu-mode-selected"/>
    <br/><span><strong>bayoen-star</strong> Mode Setting</span>    
</p>

The default is **'Game & Star+'**. The mode can be changed anytime and looks simple.

0. ~~**'Star'**: This is a basic score of **Puyo Puyo Tetris**!~~
1. **'Star+'**: Shows counted stars.
2. **'Game'** : Shows counted games.
3. **'Game & Star'**: Counts and shows games, show current stars.
4. **'Game & Star+'**: Counts and shows both games and stars. (it's default!)
5. **'Star & Star+'**: Counts and shows stars, show current stars.

In **'Star+'** and **'Game'** mode, you can make the scoreboard full-size so that it covers original scoreboard. See [Settings](#Settings). You can also export data as text file to customize your own scoreboard!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Hotkey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Hotkey

Hotkeys are few and simple.

- Menu Hotkey: Press **'m'** in main window to open menu
- Reset Hotkey: Press  **'r'** in menu to reset scores without dialog
- Overlay Hotkey: Press **'o'** in menu to enable overlay

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Streaming"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Streaming

Many people ask this, so we split the article!

See [**Here**]({{ site.lang_url }}/en/streaming.html) for streaming setting.

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Troubleshooting"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

# Trouble Shooting

## **bayoen-star** All Reset

- Can't find overlay!
- The scoreboard is broken!
- Something wrong!

Then, reset **bayoen-star** completely!

1. First, turn off **bayoen-star**
1. Delete **data.json** and **pref.json**, if they're exist
1. turn on **bayoen-star**
1. Done!

_All Reset function will be added on next update_


<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
   <img src="{{ site.lang_url }}/res/tumblr_inline_p9xbg765vf1rg6qfd_1280.png" class="box" width="30%" alt="bayoen~"/>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>