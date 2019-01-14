---
layout: bayoen-star-en
---

# Instruction

Let us give you instruction for *bayoen-star**. If you hurry, check 'Simply...?', or look out 'More Details!'

----

## Contents
- [Simply...?](#Abstract)
- [More Details](#Details)  

----

<a name="Abstract"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## Simply...? Abstract

Using **bayoen-star** is such a piece of cake! To do everything you want, just press few buttons! (from developers)

1. Run both **bayoen-star** and **Puyo Puyo Tetris**. (any order)
2. Play games in **Puyo Puyo Tetris** with any setting, any type
3. Check out the **bayoen-star** getting scores
4. Profit!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <br/><span>Following is mainwindow of <strong>bayoen-star</strong>:</span>
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
    <br/><span>You can change scoremoard mode to display types of score you want</span>
    <br/><span>Feel free for checking out other functionals!</span>
    <br/><span>You should close <strong>bayoen-star</strong> directly in traybar</span>
</p>


<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-9.png" class="shadow-box" alt="bayoen-star-example-ingame-arcade"/>
    <br/><span>And also, in puzzle leage....</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-10.png" class="shadow-box" alt="bayoen-star-example-ingame-arcade"/>
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

<a name="Details"> </a>
<a name="Functions"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## More Details

Shall we be more specific? We listed all functinoals of **bayoen-star**. Please check one by one!

----

### Detail Contents
- [Mainwindow](#Main)
    - [Conponents](#Components)
    - [Symbol](#Symbol)    
- [**bayoen-star** Functions](#Function)
- [Menu](#Menu)
    - Reset
    - [Goal](#Goal)
    - [Overlay](#Overlay)
    - [Settings](#Settings)
    - [Mode](#Mode)
- [Hotkey](#Hotkey)
- [Streaming](#Streaming)


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

### Mainwindow

Here's a instruction of **bayoen-star**'s main window.

#### Components

The main window contains this!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-initial.png" class="box" alt="bayoen-star-initial"/>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-main-en.png" class="box" alt="bayoen-star-instuction-main"/>
    <br/><span>Main window of <strong>bayoen-star</strong></span>
</p>

1. 점수판: 게임화면을 기준으로 왼쪽은 1P, 오른쪽은 2P의 점수를 표시합니다. 3가지 [심볼](#Symbol)과, 5가지 [모드](#Mode)가 있습니다. 모든 점수는 0부터 9999까지 표시할 수 있습니다. 그 이상은... 미안합니다.
2. 게임상태: **뿌요뿌요 테트리스**의 상태를 표시해줍니다. 세 종류가 있습니다.
    - **Offline**: **뿌요뿌요 테트리스**가 꺼졌습니다. 카운터를 시작하려면 **뿌요뿌요 테트리스**를 켜서 게임을 시작해주세요.
    - **Ready**: **뿌요뿌요 테트리스**가 켜져서 **바요엔-스타**가 대기중입니다. 카운터를 시작하려면 게임을 시작해주세요.
    - **Working**: 카운터가 켜졌습니다! 별이나 게임 스코어를 얻으면 점수판에 반영됩니다.
3. [메뉴](#Menu): **바요엔-스타**를 조작할 수 있는 메뉴입니다. 자세한 내용은 아래의 메뉴 설명을 봐주세요!
4. [목표점수](#Goal): 친선전, 대회 같이 여러 게임동안 점수를 집계하고 승/패를 알려줍니다. 메뉴에서 설정하고 해제할 수 있습니다. 자세한 내용은 아래의 목표설정 설명을 봐주세요!

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

<a name="Symbol"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

#### 점수판 심볼

점수판에 나오는 세가지 심볼들입니다. **뿌요뿌요 테트리스**에서 추출한 그래픽이라 이쁩니다!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-and-crown-ko.png" class="box" alt="bayoen-star-and-crown-ko"/>
    <br/><span><strong>바요엔-스타</strong>의 세 가지 심볼</span>
</p>

- 스타: 별모양으로, 현재 별 개수입니다. 게임의 별 개수와 같습니다.
- 스타+: 별모양에 더하기가 있고, 누적 별 개수입니다.
- 크라운: 왕관모양으로, 이긴 게임의 수입니다. 누적 게임 스코어라고 생각하시면 됩니다.

누적된 점수는 [초기화](#Menu), [환경설정](#Settings)에서 변경할 수 있습니다.

_***바요엔-스타**의 점수는 가상 점수입니다. 뿌요뿌요 테트리스 내부의 점수 및 밸런스에는 아무런 영향을 주지 않아요!_

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

### **바요엔-스타** 기능동작

- 감지: **바요엔-스타**는 **뿌요뿌요 테트리스** 프로그램을 감지하여 동작합니다. **뿌요뿌요 테트리스**가 꺼진 상태면 대기합니다.

- 갱신: **바요엔-스타**는 **뿌요뿌요 테트리스** 게임 플레이 중, 별이 오르는 순간의 점수변동을 계산하여 점수판에 갱신합니다.

- 저장: **바요엔-스타**에서는 게임데이터와 설정을 실시간 저장합니다. **바요엔-스타**가 강제종료 되더라도 일부정보를 복구할 수 있습니다.

- 종료: **바요엔-스타**의 메인 창을 닫으면 시스템 트레이로 최소화 됩니다. **바요엔-스타**를 완전히 종료하려면 시스템 트레이 아이콘을 우클릭해서 종료버튼을 눌러주세요!

- 메모리: (중요) **바요엔-스타**는 컴퓨터 메모리 후킹으로 동작하기 때문에, 두 가지 이슈가 있습니다:
    - **뿌요뿌요 테트리스**의 동작이 느려질까 걱정할 수 있습니다.
        - **바요엔-스타**는 상당히 가볍게 만들어진 프로그램입니다. 따라서 **뿌요뿌요 테트리스** 실행의 권장사항을 만족한다면, 방송송출까지 성능저하없이 쓸 수 있을거에요!
        
        _지나치게 느리다면 <a href="https://github.com/bayoen/bayoen-star-exe/issues" target="_blank"><strong>신고/건의</strong></a>에 신고해주세요!_
    - **뿌요뿌요 테트리스**의 내부 메모리를 조회해서 보안에 대해서 걱정할 수 있습니다.
        - **바요엔-스타**은 메모리 조작을 하지 않고, 메모리 읽기만 수행합니다.
        - **바요엔-스타**는 유저가 보는 것과 같이 게임에서 겉으로 드러나는 정보만 읽습니다.
        
        _단, 유저식별을 위해 Steam ID는 추가로 조회합니다_

여러분 **바요엔-스타**는 안전합니다! 안심하고 사용해 주세요!

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

### Menu: 메뉴

**바요엔-스타** 메뉴의 구성입니다

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-instuction-menu-selected-ko.png" class="box" alt="bayoen-star-instuction-menu-selected"/>
    <br/><span><strong>바요엔-스타</strong>의 메뉴</span>
</p>

1. **점수초기화**: '스타+'와 '크라운'을 0으로 초기화 합니다. 점수판도 바로 갱신됩니다.
2. **목표점수설정**: 목표를 정하여 여러 게임동안 점수를 집계하고 승/패를 알려줍니다. 자세한 내용은 ['Goal: 목표점수 설정'](#Goal)을 봐주세요.
3. **점수판 오버레이**: 게임화면 위에 띄울 수 있는 투명한 점수판을 띄웁니다. 자세한 내용은 ['Overlay: 점수판 오버레이'](#Overlay)을 봐주세요.
4. **환경설정**: 외형 및 점수를 변경하고, 파일 입출력 여부도 설정할 수 있습니다. 자세한 내용은 [Settings: 환경설정](#Settings)을 봐주세요.
5. **점수판 모드**: 점수판의 외형을 바꿀 수 있습니다. 자세한 내용은 [Mode: 점수판 모드 설정](#Mode)을 봐주세요.

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

#### Goal: 목표점수 설정

목표를 정하여 여러 게임동안 점수를 집계하고 승/패를 알려줍니다. 언제나 사용할 수 있고, 특히 친선전이나 대회에서 유용합니다.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-goal.png" class="box" alt="bayoen-star-menu-goal"/>
    <br/><span>목표점수설정 메뉴</span>
</p>

1. **'Set'** 목표설정: 목표설정화면을 불러옵니다. 설정이 완료되면 점수판 위에 목표가 표시됩니다.
2. **'Remove'** 목표제거: 설정된 목표를 지웁니다. 점수판에서 목표를 숨깁니다

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-goal-set.png" class="box" alt="bayoen-star-menu-goal-set"/>
    <br/><span>목표설정화면</span>
</p>

- **'Type'** 타입: 현재 지원하는 목표는 두 가지 입니다.
    - **FIRST #**: #선승 입니다! #점을 먼저 얻으면 이깁니다.
    - **TOTAL #**: #점다선승입니다! 선수들의 점수합이 #점이 됐을때 점수가 높은 사람이 이깁니다.
- **'Counter'** 카운터: 목표점수는 '스타+' 혹은 '크라운'으로 설정할 수 있습니다. 값은 0부터 9999까지 설정할 수 있습니다!

<p align="center">
    <span>목표설정이 완료되면 이런 식으로 표시됩니다</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-mode-2-fit.png" class="box" alt="bayoen-star-example-mode-2-fit"/>
    <br/><span><strong>왕관 10선승 (First, Crown, 10 Scores)</strong></span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-total-none.png" class="box" alt="bayoen-star-example-goal-total-none"/>
    <br/><span><strong>별 20점 다선승 (Total, Star+, 20 Scores)</strong></span>    
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

**바요엔-스타**은 게임화면 위에 띄울 수 없습니다... 대신, 투명한 **오버레이** 점수판을 띄울 수 있습니다!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-overlay-menu.png" class="box" alt="bayoen-star-overlay-menu"/>
    <br/><span><strong>오버레이</strong> 화면 및 보조메뉴</span>
</p>

**오버레이**는 기존 점수판을 복제한 것으로, 여러기능이 있습니다!

- **이동**: 마우스로 **오버레이**를 드래그하면 위치를 옮길 수 있습니다
- **크기조절**: 마우스를 **오버레이** 위로 올린 상태에서, **마우스 휠**로 크기를 줄이거나 키울 수 있습니다
- **보조메뉴**: **오버레이**를 마우스 우클릭하면 보조메뉴가 나옵니다
    - **'Fixed'** 고정하기: **오버레이**를 고정시킵니다. 고정된 상태면 이동 및 크기조절을 할 수 없습니다. 고정된 상태라면, **뿌요뿌요 테트리스**의 창이 움직이면 똑같이 오버레이도 따라갑니다!
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

환경설정 화면입니다. **바요엔-스타**의 외형 및 점수를 변경하고, 파일 입출력 여부도 설정할 수 있습니다.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-settings-ko.png" class="box" alt="bayoen-star-settings-ko"/>
    <br/><span><strong>환경설정</strong> 화면</span>
</p>

**A. 주요설정**
1. **항상 위에**: 체크하면 **바요엔-스타**를 항상 위로 둡니다
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
    <br/><span><strong>바요엔-스타</strong>의 점수판 모드 설정</span>    
</p>

기본값은 **'Game & Star+'** 입니다. 모드 변경으로 점수만 깔끔하게 볼 수 있습니다.

0. ~~**'Star'** 스타: 이 점수는 **뿌요뿌요 테트리스**에서 기본지원 합니다!~~
1. **'Star+'** 스타+: 별을 세어서 보여줍니다.
2. **'Game'** 크라운: 이긴 게임을 세어줍니다.
3. **'Game & Star'** 크라운과 스타: 이긴 게임을 세고, 현재 별을 보여줍니다.
4. **'Game & Star+'** 크라운과 스타+: 이긴 게임과 별 모두 세어줍니다. (기본값입니다!)
5. **'Star & Star+'** 스타와 스타+: 별을 세고, 현재별을 보여줍니다.

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

There were someone seeking this, we split the article!

방송송출용 설정에 대한 내용은 [Here]({{ site.lang_url }}/en/streaming.html)서 봐주세요.

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
   <img src="{{ site.lang_url }}/res/dailycarbuncle_kirbuncle.png" class="box" width="30%" alt="bayoen~"/>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>