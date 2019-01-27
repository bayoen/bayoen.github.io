---
layout: bayoen-star-en
---

# Guide

Let us give you instructions for **bayoen-star**. If you are in hurry, check 'Summary,' or look at 'More Details!'

<div class="toc">
    <h2>Contents</h2>
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

Shall we be more specific? We listed all functinoals of **bayoen-star**. Please check one by one!

<div class="toc-sub">
    <h2>Detail Contents</h2>
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
                <li><strong>bayoen-star</strong> all reset</li>
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
    - **TOTAL #**: A match with total **#score**! The plaer who get more scores overall **#score** match.
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

#### Overlay: 점수판 오버레이

**bayoen-star**은 게임화면 위에 띄울 수 없습니다... 대신, 투명한 **오버레이** 점수판을 띄울 수 있습니다!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-overlay-menu.png" class="box" alt="bayoen-star-overlay-menu"/>
    <br/><span><strong>오버레이</strong> 화면 및 보조메뉴</span>
</p>

**오버레이**는 기존 점수판을 복제한 것으로, 여러기능이 있습니다!

- **이동**: 마우스로 **오버레이**를 드래그하면 위치를 옮길 수 있습니다
- **크기조절**: 마우스를 **오버레이** 위로 올린 상태에서, **마우스 휠**로 크기를 줄이거나 키울 수 있습니다
- **보조메뉴**: **오버레이**를 마우스 우클릭하면 보조메뉴가 나옵니다
    - **'Fixed'** 고정하기: **오버레이**를 고정시킵니다. 고정된 상태면 이동 및 크기조절을 할 수 없습니다. 고정된 상태라면, **Puyo Puyo Tetris**의 창이 움직이면 똑같이 오버레이도 따라갑니다!
    - **'Reset'** 초기화: 점수를 초기화 합니다. 실수로 누르는 것을 방지하게 위해 '시프트'키를 누른상태에서 눌러야 동작합니다!
    - **'Close'** 닫기: **오버레이**를 닫습니다

_여기서 소개드린 오버레이는 **송출용 오버레이**가 아닙니다! 방송에서 오버레이를 사용하고 싶으시면 [**'방송설정'**]({{ site.lang_url }}/ko/streaming.html)을 봐주세요!_

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-arcade.png" class="shadow-box" alt="bayoen-star-example-ingame-arcade"/>
    <br/><span>이렇게 <strong>오버레이</strong>를 띄울 수 있어요!</span>
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

#### Settings: 환경설정

환경설정 화면입니다. **bayoen-star**의 외형 및 점수를 변경하고, 파일 입출력 여부도 설정할 수 있습니다.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-settings-ko.png" class="box" alt="bayoen-star-settings-ko"/>
    <br/><span><strong>환경설정</strong> 화면</span>
</p>

**A. 주요설정**
1. **항상 위에**: 체크하면 **bayoen-star**를 항상 위로 둡니다
2. **자동 숨기기***: 체크하면 게임 중이 아닐 때 (**'Working'** 상태), 점수판을 숨깁니다
3. **텍스트 출력***: 체크하면 텍스트 파일로 결과를 출력합니다
4. **점수판 크기조절***: 체크하면 점수판의 크기를 최대크기로 고정합니다.
5. **크로마키 설정***: 여러가지 크로마키를 설정할 수 있습니다

**B. 점수 모니터**
- **'Star+', 'Crown'** 점수: **'스타+'**와 **'크라운'**을 수정할 수 있습니다. '스타'는 읽기전용입니다!
- **'Win Count'**: 게임을 이기기 위한 별 개수 입니다. 읽기전용입니다!
- **'Load'** 불러오기(갱신): 강제로 현재 **'스타+'**와 **'크라운'** 점수를 갱신합니다.
- **'Save'** 저장: **'스타+'**와 **'크라운'** 점수를 현재 값으로 저장합니다.

_환경설정 중 '*'가 있는 항목은 방송설정을 위한 것이니, 더 자세한 내용은 [**'방송설정'**]({{ site.lang_url }}/ko/streaming.html)을 확인해 주세요!_

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

#### Mode: 점수판 모드 설정

점수판의 외형을 바꿀 수 있습니다. 모드 설정은 가능한 모든 점수판 형태를 지원합니다.

<p align="center">    
    <img src="{{ site.lang_url }}/res/bayoen-star-and-crown-ko.png" class="box" alt="bayoen-star-and-crown"/>
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-mode-selected.png" class="box" alt="bayoen-star-menu-mode-selected"/>
    <br/><span><strong>bayoen-star</strong>의 점수판 모드 설정</span>    
</p>

기본값은 **'Game & Star+'** 입니다. 모드 변경으로 점수만 깔끔하게 볼 수 있습니다.

0. ~~**'Star'**: This is a basic score of **Puyo Puyo Tetris**!~~
1. **'Star+'**: Counts and shows stars.
2. **'Game'** : Counts and shows games.
3. **'Game & Star'**: 이긴 게임을 세고, 현재 별을 보여줍니다.
4. **'Game & Star+'**: 이긴 게임과 별 모두 세어줍니다. (it's default!)
5. **'Star & Star+'**: 별을 세고, 현재별을 보여줍니다.

**'Star+'** 모드나 **'Game'** 모드의 크기가 작으면 [환경설정](#Settings)에서 키울 수도 있습니다. 텍스트 출력으로 커스텀할 수도 있어요!

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

## 단축키

Hotkey... is still on progress...

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

## 방송설정

Many people ask this, so we split the article!

See [Here]({{ site.lang_url }}/en/streaming.html) for streaming setting.

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