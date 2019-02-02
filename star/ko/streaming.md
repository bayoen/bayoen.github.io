---
layout: bayoen-star-ko
---

# 방송설정

인터넷 방송인을 위한 **바요엔-스타** 송출설정을 알려드립니다.

<div class="toc">
    <h2>목차</h2>
    <ul>
        <li><a href="#Example">인터넷 방송화면 예시</a></li>
        <li><a href="#ChromaKey">크로마키 설정</a>
            <ol>
                <li><a href="#StarChromaKey"><strong>바요엔-스타</strong>에서 크로마키 설정</a></li>
                <li><a href="#StreamChromaKey">송출프로그램에서 크로마키 설정</a>
                    <ul>
                        <li><a href="#OBSChromaKey">OBS 캡처 및 크로마키 설정</a></li>
                        <li><a href="#XSplitChromaKey">XSplit 캡처 및 크로마키 설정</a></li>
                    </ul>
                </li>
            </ol>
        </li>
        <li><a href="#Detail">기타 세부 설정</a>
            <ul>
                <li>항상 위에, 자동 숨기기, 텍스트 출력, 점수판 크기 조절, 크로마 키 설정</li>
            </ul>
        </li>
        <li><a href="#Custom">커스텀 설정</a></li>        
    </ul>
</div>

<!-- ## 목차
- [크로마키 설정](#ChromaKey)
    1. [**바요엔-스타**에서 크로마키 설정](#StarChromaKey)
    2. [송출프로그램에서 크로마키 설정](#StreamChromaKey) -->

----

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

<a name="Example"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## 인터넷 방송화면 예시

방송에서 사용할 수 있는 예시들을 소개합니다.

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-a.png" class="shadow-box" alt="bayoen-star-example-stream-ingame"/>
    <br/><span><strong>방송용:</strong> 제일 간단한 형태</span>
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-b.png" class="shadow-box" alt="bayoen-star-example-stream-ingame-with-friend"/>
    <br/><span><strong>대회용, 친선전용:</strong> 별 15 선승 경기</span>
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-c.png" class="shadow-box" alt="bayoen-star-example-stream-ingame-league"/>
    <br/><span><strong>퍼즐리그:</strong> 승/패 집계 10번 이기기</span>
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-custom.png" class="box" alt="bayoen-star-example-custom"/>
    <br/><span><strong>커스텀:</strong> 나만의 점수판!</span>
</p>

이렇게 꾸미고 싶으신가요? 아래 설명을 따라하시면 쉽게 할 수 있어요!

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>


<a name="ChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## 크로마키 설정

**바요엔-스타**를 방송용으로 쓸 때, **'오버레이'**가 아니라 **메인창**을 캡처해야 합니다. '나는 오버레이로 보고, 시청자들은 캡처된 메인창으로 본다'라고 생각하시면 됩니다!

_이 설정만 적용하셔도 충분히 송출용으로 쓸 수 있습니다. 더 디테일한 설정을 하고 싶으시면 다른 설정들도 살펴주세요!_

<a name="StarChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### 1. **바요엔-스타**에서 크로마키 설정

먼저 **바요엔-스타**에서 크로마키 설정을 합니다. '메뉴(Menu) > 설정(Settings)'에서 크로마키(Chroma Key) 설정 하시면 됩니다.

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-settings-chromakey-selected.png" class="box" alt="bayoen-star-settings-chromakey-selected"/>
    <br/><span><strong>크로마키 설정창</strong></span>
</p>

- None: 크로마키를 해제합니다
- Magenta: 자홍색으로 크로마키를 설정합니다. [OBS](https://obsproject.com/ko)에서 최적의 색상입니다.
- Green: 초록색으로 크로마키를 설정합니다. [XSplit](https://www.xsplit.com/ko)에서 최적의 색상입니다.
- Blue: 파란색으로 크로마키를 설정합니다. [XSplit](https://www.xsplit.com/ko)에서 최적의 색상입니다.

<div class="box">
    <div class="column3">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-chroma.png" class="shadow-box" width="95.4%" alt="bayoen-star-example-chroma"/>
        <br/><span><strong>자홍색</strong> 크로마키</span>
    </div>
    <div class="column3">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-green.png" class="shadow-box" alt="bayoen-star-example-goal-first-green"/>
        <br/><span><strong>초록색</strong> 크로마키</span>
    </div>
    <div class="column3">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-blue.png" class="shadow-box" alt="bayoen-star-example-goal-first-blue"/>
        <br/><span><strong>파란색</strong> 크로마키</span>
    </div>
</div>

<a name="StreamChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### 2. 송출프로그램에서 크로마키 설정

송출프로그램에서 크로마키 설정하는 법을 순서대로 알려드립니다.

1. **'bayoen-star' (bayoen-star.exe)** 창을 캡처합니다.
1. 캡처한 창을 **바요엔-스타**와 같은 색의 크로마키로 설정합니다.
<!-- 1. 캡처한 창의 제목표시줄을 잘라줍니다. 30픽셀만 잘라주세요!

    _위쪽 영역을 더 자르게 되면 점수판이 잘리게 됩니다. 이 외의 다른 꾸미기는 자유롭게 해주세요!_ -->
1. 끝났습니다!

OBS나 XSplit를 사용하고 계시다면 아래의 설명에 따라하시면 됩니다!

<a name="OBSChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

- OBS (Open Broadcaster Software) 캡쳐 및 크로마키 설정
    1. 메인화면을 송출창에 추가합니다.<br/>
        - **소스 목록 > 윈도우 캡쳐 > 윈도우 '[bayoen-star.exe]: bayoen-star'**
    1. **'바요엔-스타-캡처'**나 마음에 드는 이름으로 바꿔줍니다.
    1. **'바요엔-스타-캡처'**에 크로마키를 설정합니다.<br/>
        - **우클릭 > 필터 > 추가 '+' > 크로마 키 > 키 색상 형식 > '바요엔-스타'의 크로마키와 같은 색**
        - OBS에서는 **자홍색(magenta)**을 권장합니다
    <!-- 1. **'바요엔-스타-캡처'**의 제목표시줄을 잘라줍니다.<br/>
        - **우클릭 > 변환 > 변환 편집 > 자르기 > 위 > 30 픽셀** -->
    1. 끝났습니다! **'바요엔-스타-캡처'**를 원하는 크기로 원하는 곳에 두면 됩니다!

    _*OBS 윈도우 캡쳐에서 '윈도우 일치 우선순위'는 '창 제목이 일치해야 합니다'로 해주시는게 좋습니다!_

<p align="center">
    <img src="{{ site.lang_url }}/res/obs-chromakey-example-1.png" class="shadow-box" width="48%" alt="obs-chromakey-example-1"/>
    <img src="{{ site.lang_url }}/res/obs-chromakey-example-2.png" class="shadow-box" width="48%" alt="obs-chromakey-example-2"/>
    <br/><span><strong>OBS</strong> 캡처 및 크로마키 설정 적용</span>
    <br/><span>오버레이가 아닌 메인 창을 캡처하셔야 합니다!</span>
</p>


<a name="XSplitChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

- XSplit 캡처 및 크로마키 설정
    1. 메인화면을 송출창에 추가합니다.<br/>
        - **소스 추가 > Screen 캡쳐 > 윈도우 캡쳐 'bayoen-star (bayoen-star.exe)'**
    1. **'바요엔-스타-캡처'**나 마음에 드는 이름으로 바꿔줍니다.
    1. **'바요엔-스타-캡처'**에 크로마키를 설정합니다.<br/>
        - **설정 > 색 > 키 > 크로마키 > '바요엔-스타'의 크로마키와 같은 색**
        - XSplit에서는 **초록색(Green), 파란색(Blue)**을 권장합니다
    1. **'바요엔-스타-캡처'**의 제목표시줄을 잘라줍니다.<br/>
        - **설정 > 레이아웃 > 사진/삽화의 불필요한 부분 다듬기 > 상단 > 39 포인트 (30 픽셀)**
    1. 끝났습니다! **'바요엔-스타-캡처'**를 원하는 크기로 원하는 곳에 두면 됩니다!

<p align="center">
    <img src="{{ site.lang_url }}/res/xsplit-chromakey-example-1.png" class="shadow-box" width="48%" alt="xsplit-chromakey-example-1"/>
    <img src="{{ site.lang_url }}/res/xsplit-chromakey-example-2.png" class="shadow-box" width="48%" alt="xsplit-chromakey-example-2"/>
    <br/><span><strong>XSplit</strong> 캡처 및 크로마키 적용</span>
    <br/><span>오버레이가 아닌 메인 창을 캡처하셔야 합니다!</span>
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

## 기타 세부 설정

사용법에서 설명드렸던 내용을 좀 더 자세히 소개해드립니다.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-settings-streaming-ko.png" class="box" alt="bayoen-star-settings-streaming"/>
    <br/><span>인터넷 방송을 위한 <strong>바요엔-스타</strong>의 메뉴</span>
</p>

1. **항상 위에**: 체크하면 **바요엔-스타**를 항상 위로 둡니다. 송출 중에 조작하기 편하게 항상 위에 띄울 수 있습니다.
1. **자동 숨기기**: 체크하면 **뿌요뿌요 테트리스**가 꺼져 있을 때 (**'Offline'** 상태), 점수판을 숨깁니다. 송출 중에 크로마키 설정이 돼있다면, **뿌요뿌요 테트리스**가 꺼져 있을 때, 자연스럽게 점수판을 숨겨줍니다.
1. **텍스트 출력**: 체크하면 텍스트 파일에 각 데이터를 숫자로 출력합니다. 데이터가 필요하신 분 혹은 커스텀 점수판이 필요한 분에게 유용합니다.
    - **바요엔-스타** 경로의 **'export'**에 **UTF-8** 형식으로 출력합니다.

    <p align="center">
        <img src="{{ site.lang_url }}/res/bayoen-star-export-list.png" class="shadow-box" alt="bayoen-star-export-list"/>
        <br/><span>출력파일들의 목록</span>
    </p>

    _더 자세한 내용은 [커스텀 설정](#Custom)을 살펴보세요!_
1. **점수판 크기조절**: 체크하면 점수판의 크기를 최대크기로 고정합니다. **바요엔-스타**의 점수판이 작아서 **뿌요뿌요 테트리스**의 점수판을 온전히 가리지 못할 때 유용합니다. 
    
    <p align="center">
        <img src="{{ site.lang_url }}/res/bayoen-star-example-setting-fit.gif" class="shadow-box" alt="bayoen-star-example-setting-fit"/>
        <br/><span>점수판 크기 조절/비교</span>
    </p>

    <p align="center">
        <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-b.png" class="shadow-box" alt="bayoen-star-example-ingame-league"/>
        <br/><span><strong>바요엔-스타</strong> 점수판 크기 조절, 인터넷 방송화면</span>
    </p>
1. **크로마키 설정**: 여러가지 크로마키를 설정할 수 있습니다. 자세한 내용은 [크로마키 설정](#ChromaKey)을 살펴보세요!

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

## 커스텀 설정

나만의 송출용 스킨은 가능할까요? 물론 가능합니다! **바요엔-스타**에서 텍스트 형태로 점수를 실시간 출력을 하고, 그 파일을 송출 프로그램으로 읽어서 표시할 수 있습니다. 커스텀 스킨은 송출 프로그램으로 구성하시고 점수는 '텍스트 파일 읽기' 기능으로 불러오시면 됩니다.

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-export-list.png" class="shadow-box" alt="bayoen-star-export-list"/>
    <br/><span>출력파일들의 목록</span>
</p>

<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-example-custom.png" class="box" alt="bayoen-star-example-custom"/>
    <br/><span><strong>바요엔-스타</strong> 커스텀 점수판 캡처</span>
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

<p align="center">
   <img src="{{ site.lang_url }}/res/tumblr_inline_pdf1kiycQE1rg6qfd_1280.png" class="box" width="30%" alt="carbuncle-except-hes-a-tetrimino"/>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>