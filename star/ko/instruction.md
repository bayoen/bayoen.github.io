---
layout: bayoen-star-ko
---

# 사용법

**바요엔-스타**는 사용법을 알려드립니다. 시간이 없으신 분은 '간단하게' 보시고, 더 '자세하게' 내용을 알고싶은 분은 더 아래로 내려주세요!

----

## 목차
- [간단하게](#Abstract)
- [자세하게](#Details)  

----

<a name="Abstract"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## 간단하게

**바요엔-스타**는 정말 사용하기 쉽습니다! 버튼 몇 개만 누르면 하고 싶은 걸 모두 할 수 있을 거에요! (개발자 생각입니다)

1. **바요엔-스타**와 **뿌요뿌요 테트리스**를 켭니다. (순서는 상관없어요)
2. **뿌요뿌요 테트리스**에서 별다른 설정 없이 게임을 시작합니다. (게임 종류도 상관없어요)
3. **바요엔-스타**에 점수가 오르는 걸 확인합니다!
4. 끝!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <br/><span><strong>바요엔-스타</strong>의 메인화면은 이런 구성입니다</span>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-main-ko.png" class="box" alt="bayoen-star-initial"/>
    <br/><span>직관적인 구성으로 누구나 쉽게 쓸 수 있습니다 (역시 개발자 생각입니다)</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <br/><span><strong>메뉴</strong>를 눌러서 점수를 초기화하거나, 목표점수를 설정하거나, 환경설정 및 점수판모드를 바꿀 수 있습니다!</span>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-menu-selected-ko.png" class="box" alt="bayoen-star-instuction-menu-selected"/>
        <br/><span>친선전이나 대회로 <strong>N선승</strong>을 하고 싶으시면 목표점수설정을 꼭 해보세요!</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <span><strong>바요엔-스타</strong>의 점수판에는 이런 것들이 나옵니다!</span>    
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-and-crown-ko.png" class="box" alt="bayoen-star-and-crown"/>
    <img src="{{ site.lang_url }}/res/bayoen-star-menu-mode-selected.png" class="box" alt="bayoen-star-menu-mode-selected"/>
    <br/><span>점수판 모드를 바꿔서 내가 원하는 점수만 표시할 수 있습니다</span>
    <br/><span>그 밖의 다른 기능들도 살펴보세요!</span>
    <br/><span>끌 때는 작업표시줄에서 종료해주세요~</span>
</p>


<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-9.png" class="shadow-box" alt="bayoen-star-example-ingame-arcade"/>
    <br/><span>퍼즐리그에서도..</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-10.png" class="shadow-box" alt="bayoen-star-example-ingame-arcade"/>
    <br/><span>이렇게 즐겁게 할 수 있답니다!</span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<p align="center">
    <span><strong>진짜 끝!</strong></span>    
</p>

<a name="Details"> </a>
<a name="Functions"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## 자세하게

이제 본격적으로 알아볼까요? **바요엔-스타** 기능들을 정리했습니다 하나씩 눌러보세요!

----

### 세부목차
- [메인화면](#Main)
    - [화면구성](#MainWindow)
    - [점수판 심볼](#Symbol)    
- [**바요엔-스타** 기능동작](#Function)
- [Menu: 메뉴](#Menu)
    - Reset: 점수 초기화
    - [Goal: 목표점수 설정](#Goal)
    - [Overlay: 점수판 오버레이](#Overlay)
    - [Settings: 환경설정](#Settings)
    - [Mode: 점수판 모드 설정](#Mode)
- [단축키](#Hotkey)
- [방송설정](#Streaming)


----

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Main"> </a>
<a name="MainWindow"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### 메인화면

**바요엔-스타**의 메인화면에 대한 설명입니다.

#### 화면구성

메인화면의 구성입니다

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-initial.png" class="box" alt="bayoen-star-initial"/>
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-instuction-main-ko.png" class="box" alt="bayoen-star-instuction-main"/>
    <br/><span><strong>바요엔-스타</strong>의 메인화면</span>
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
        
        _지나치게 느려지면 <a href="https://github.com/bayoen/bayoen-star-exe/issues" target="_blank"><strong>신고/건의</strong></a>에 신고해주세요!_
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

1. 점수초기화: '스타+'와 '크라운'을 0으로 초기화 합니다. 점수판도 바로 갱신됩니다.
2. 목표점수설정: 목표를 정하여 여러 게임동안 점수를 집계하고 승/패를 알려줍니다. 자세한 내용은 ['Goal: 목표점수 설정'](#Goal)을 봐주세요!
3. 점수판 오버레이: 
4. 환경설정: 
5. 점수판 모드: 

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

- 현재 지원하는 목표는 두 가지 입니다.
    - **FIRST #**: #선승 입니다! #점을 먼저 얻으면 이깁니다.
    - **TOTAL #**: #점다선승입니다! 선수들의 점수합이 #점이 됐을때 점수가 높은 사람이 이깁니다.
- 목표점수는 '스타+' 혹은 '크라운'으로 설정할 수 있습니다. 값은 0부터 9999까지 설정할 수 있습니다!

<p align="center">
    <span>목표설정이 완료되면 이런 식으로 표시됩니다</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-mode-2-fit.png" class="box" alt="bayoen-star-example-mode-2-fit"/>
    <br/><span>왕관 10선승 (First, Crown, 10 Scores)</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-total-none.png" class="box" alt="bayoen-star-example-goal-total-none"/>
    <br/><span>별 20점 다선승 (Total, Star+, 20 Scores)</span>    
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

**바요엔-스타**의 메인창은 투명하게 할 수 없습니다... 대신, 따로 투명한 **오버레이** 전용창을 띄울 수 있습니다!

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-overlay-menu.png" class="shadow-box" alt="bayoen-star-overlay-menu"/>
    <br/><span><strong>오버레이</strong> 화면 및 보조메뉴</span>
</p>

**오버레이**에도 여러기능이 있습니다!

- 이동: 마우스로 **오버레이**를 드래그하면 위치를 옮길 수 있습니다
- 크기조절: 마우스를 **오버레이** 위로 올린 상태에서, 마우스 휠로 크기를 줄이거나 키울 수 있습니다
- 보조메뉴: 
    - 'Fixed' 고정하기: **오버레이**를 고정시킵니다. 고정된 상태면 이동 및 크기조절을 할 수 없습니다. 고정된 상태라면, **뿌요뿌요 테트리스**의 창이 움직이면 똑같이 오버레이도 따라갑니다!
    - 'Reset' 초기화: 점수를 초기화 합니다. 실수로 누르는 것을 방지하게 위해 '시프트'키를 누른상태에서 눌러야 동작합니다!
    - 'Close' 닫기: **오버레이**를 닫습니다

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

찾으시는 분들이 많아 따로 항목을 만들었습니다!

방송송출용 설정에 대한 내용은 [여기]({{ site.lang_url }}/ko/streaming.html)서 봐주세요.

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