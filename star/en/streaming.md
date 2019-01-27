---
layout: bayoen-star-en
---

# For Streaming

Let us introduce a **bayoen-star** setting for streamer.

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-a.png" class="shadow-box" alt="bayoen-star-example-ingame-league"/>
    <br/><span><strong>Streaming Capture #1:</strong> <strong>bayoen-star</strong> Mainwindow Capture</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<div class="toc">
    <h2>Content</h2>
    <ul>
        <li><a href="#ChromaKey">Chroma Key Setting</a>
            <ol>
                <li><a href="#StarChromaKey">Chroma Key in <strong>bayoen-star</strong></a></li>
                <li><a href="#StreamChromaKey">Chroma Key in Streaming App.</a>
                    <ul>
                        <li><a href="#OBSChromaKey">OBS Capture and Chroma Key</a></li>
                        <li><a href="#XSplitChromaKey">XSplit Capture and Chroma Key</a></li>
                    </ul>
                </li>
            </ol>
        </li>
        <li><a href="#Detail">Detail Setting</a>
            <ul>
                <li>Top Flag, Auto Hide, Export Text, Size Adjustment, Chroma Key</li>
            </ul>
        </li>
        <li><a href="#Custom">Custom Setting</a></li>
    </ul>
</div>

----

<a name="ChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Chroma Key Setting

To use **bayoen-star** in your stream, you have to capture **'main window'** not **'overlay'**. You would better think that 'I see the overlay, viewers see the captured main window'!

_Reading this section is enough for streaming. If you need more details, see other instructions!_

<a name="StarChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### 1. Chroma Key in **bayoen-star**

First, set chroma key in **bayoen-star**. Select chroma key in 'Menu > Settings'.

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-settings-chromakey-selected.png" class="box" alt="bayoen-star-settings-chromakey-selected"/>
    <br/><span><strong>Chroma Key Setting</strong></span>
</p>

- None: Release chroma key.
- Magenta: Set magenta chroma key. optimized in [OBS](https://obsproject.com/ko).
- Green: Set green chroma key. optimized in [XSplit](https://www.xsplit.com/ko).
- Blue: Set blue chroma key. optimized in [XSplit](https://www.xsplit.com/ko).

<div class="box">
    <div class="column3">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-chroma.png" class="shadow-box" width="95.4%" alt="bayoen-star-example-chroma"/>
        <br/><span><strong>Magenta</strong> Chroma Key</span>
    </div>
    <div class="column3">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-green.png" class="shadow-box" alt="bayoen-star-example-goal-first-green"/>
        <br/><span><strong>Green</strong> Chroma Key</span>
    </div>
    <div class="column3">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-blue.png" class="shadow-box" alt="bayoen-star-example-goal-first-blue"/>
        <br/><span><strong>Blue</strong> Chroma Key</span>
    </div>
</div>

<a name="StreamChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### 2. Chroma Key in Streaming App.

Let us introduce how to set chroma key in your streaming application:

1. Capture **'bayoen-star' (bayoen-star.exe)** window
1. Set chroma key of **bayoen-star** and the captured window with the same color
1. Crop the title bar of the captured window about 30 pixels!

    _If you crop more than 30 pixels, the scoreboard can be cropped. feel free to change anything except that_
1. Done!

If you are using OBS or XSplit, see the guide below!

<a name="OBSChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

- OBS (Open Broadcaster Software) Capture and Chroma Key
    1. Add the main window in OBS.<br/>
        - **Sources > Window Capture > Window '[bayoen-star.exe]: bayoen-star'**
    1. Rename it with **'bayoen-star-capture'** or your favorite.
    1. Set chroma key **'bayoen-star-capture'**.<br/>
        - **Right-click > Filter > Add '+' > Chroma Key > Key Color Type > The same color of Chroma Key of 'bayoen-star'**
        - OBS recommends **Magenta**.
    1. Crop title bar of **'bayoen-star-capture'**.<br/>
        - **Right-click > Transform > Edit Transform > Crop > Top > 30 Pixels**
    1. It's done! Place **'bayoen-star-capture'** anywhere with any size!

    _*Tip: In OBS window capture, you need to select 'Window title must match' for 'Window Match Priority'!_

<p align="center">
    <img src="{{ site.lang_url }}/res/obs-chromakey-example-1.png" class="shadow-box" width="48%" alt="obs-chromakey-example-1"/>
    <img src="{{ site.lang_url }}/res/obs-chromakey-example-2.png" class="shadow-box" width="48%" alt="obs-chromakey-example-2"/>
    <br/><span><strong>OBS</strong> Capture and Chroma Key Setting</span>
    <br/><span>You have to capture the main window not overlay!</span>
</p>


<a name="XSplitChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

- XSplit Capture and Chroma Key
    1. Add the main window in XSplit.<br/>
        - **Add source > Screen capture > Window Capture 'bayoen-star (bayoen-star.exe)'**
    1. Rename it with **'bayoen-star-capture'** or your favorite.
    1. Set chroma key **'bayoen-star-capture'**.<br/>
        - **Settings > Color > Keying > Chroma Key > The same color of Chroma Key of 'bayoen-star'**
        - XSplit recommends **Green, Blue**
    1. Crop title bar of **'bayoen-star-capture'**.<br/>
        - **Settings > Layout > Cropping > Top > 39 Point (30 Pixels)**
    1. It's done! Place **'bayoen-star-capture'** anywhere with any size!

<p align="center">
    <img src="{{ site.lang_url }}/res/xsplit-chromakey-example-1.png" class="shadow-box" width="48%" alt="xsplit-chromakey-example-1"/>
    <img src="{{ site.lang_url }}/res/xsplit-chromakey-example-2.png" class="shadow-box" width="48%" alt="xsplit-chromakey-example-2"/>
    <br/><span><strong>XSplit</strong> Capture and Chroma Key Setting</span>
    <br/><span>You have to capture the main window not overlay!</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Detail"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Detail Setting

Here is specific information of setting guide.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-settings-streaming-en.png" class="box" alt="bayoen-star-settings-streaming"/>
    <br/><span><strong>bayoen-star</strong> Menu for Internet Streaming</span>
</p>

1. **Top Flag**: If checked, Set **bayoen-star** top most. It help to control easily in streaming.
1. **Auto Hide**: If checked, hide scoreboard when you are not in game (**'Working'** status). In your stream, It hides scoreboard when **Puyo Puyo Tetris** is offline.
1. **Export Text**: If checked, export score data into text file. It helps who need score data or would like to make a custom scoreboard.
    - It export files in **'export'** directory of **bayoen-star**'s path with **UTF-8** format.

    <p align="center">
        <img src="{{ site.lang_url }}/res/bayoen-star-export-list.png" class="shadow-box" alt="bayoen-star-export-list"/>
        <br/><span>List of exporting file</span>
    </p>

    _See [**'Custom Setting'**](#Custom) for more details!_
1. **Size Adjustment**: If checked, maximize the size of scoreboard. It is useful when the scoreboard of **bayoen-star** does not fit the scoreboard of **Puyo Puyo Tetris**. 

    <p align="center">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-setting-fit.gif" class="shadow-box" alt="bayoen-star-example-setting-fit"/>
        <br/><span>Size Adjustment of Scoreboard</span>
    </p>

    <p align="center">
        <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-b.png" class="shadow-box" alt="bayoen-star-example-ingame-league"/>
        <br/><span><strong>Streaming Capture #2:</strong> <strong>bayoen-star</strong> Size Adjustment of Scoreboard</span>
    </p>
1. **Chroma Key**: Set/clear chroma key color for your internet stream. See [Chroma Key Setting](#ChromaKey)!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Custom"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Custom Setting

Can I make my own skin for streaming? Yes, we can! **bayoen-star** can export score data with text file in real-time, the stream application can read it and display the scores. You should make a custom skin using the stream app. and show scores using 'Read from file' function.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-export-list.png" class="shadow-box" alt="bayoen-star-export-list"/>
    <br/><span>List of exporting file</span>
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-custom.png" class="box" alt="bayoen-star-example-custom"/>
    <br/><span><strong>Streaming Capture #3:</strong> <strong>bayoen-star</strong> Custom Scoreboard Capture</span>
</p>


<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
   <img src="{{ site.lang_url }}/res/tumblr_inline_pdf1kiycQE1rg6qfd_1280.png" class="box" width="30%" alt="carbuncle-except-hes-a-tetrimino"/>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>