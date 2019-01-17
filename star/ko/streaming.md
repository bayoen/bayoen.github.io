---
layout: bayoen-star-ko
---

# 방송설정

인터넷 방송인을 위한 **바요엔-스타** 송출설정을 알려드립니다.

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-ingame-league-a.png" class="shadow-box" alt="bayoen-star-example-ingame-league"/>
    <br/><span><strong>인터넷 방송화면 캡처 #1</strong></span>
</p>

<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

----

## 목차
- [크로마키 설정](#ChromaKey)
    1. [**바요엔-스타**에서 크로마키 설정](#ChromaKey1)
    2. [송출프로그램에서 크로마키 설정](#ChromaKey2)
- [세부 설정](#Detail)
- [커스텀 설정](#Custom)

----

<a name="ChromaKey"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

## 크로마키 설정

**바요엔-스타**를 방송용으로 쓸 때, **'오버레이'**가 아니라 **메인창**을 캡처해야 합니다. '나는 오버레이로 보고, 시청자들은 캡처된 메인창으로 본다'라고 생각하시면 됩니다!

_이 설정만 적용하셔도 충분히 송출용으로 쓸 수 있습니다. 더 디테일한 설정을 하고 싶으시면 다른 설정들도 살펴주세요!_

<a name="ChromaKey1"> </a>
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

<p align="center">
    <table>
        <tr>
            <th>
                <p align="center">
                    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-chroma.png" class="box" alt="bayoen-star-example-chroma"/>
                    <br/><span><strong>자홍색</strong> 크로마키</span>
                </p>
            </th>
            <th>
                <p align="center">
                    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-green.png" class="box" alt="bayoen-star-example-goal-first-green"/>
                    <br/><span><strong>초록색</strong> 크로마키</span>
                </p>
            </th>
                        <th>
                <p align="center">
                    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-blue.png" class="box" alt="bayoen-star-example-goal-first-blue"/>
                    <br/><span><strong>파란색</strong> 크로마키</span>
                </p>
            </th>
        </tr>
    </table>
</p>

<!-- <p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-chroma.png" class="box" alt="bayoen-star-example-chroma"/>
    <br/><span><strong>자홍색</strong> 크로마키</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-green.png" class="box" alt="bayoen-star-example-goal-first-green"/>
    <br/><span><strong>초록색</strong> 크로마키</span>
</p>

<p align="center">
    <br/><img src="{{ site.lang_url }}/res/bayoen-star-example-goal-first-blue.png" class="box" alt="bayoen-star-example-goal-first-blue"/>
    <br/><span><strong>파란색</strong> 크로마키</span>
</p> -->

<a name="ChromaKey2"> </a>
<p align="center">
.<br/><br/>
.<br/><br/>
.
</p>

### 2. 송출프로그램에서 크로마키 설정

송출프로그램에서 크로마키 설정하는 법을 순서대로 알려드립니다.

1. **'bayoen-star' (bayoen-star.exe)** 창을 캡처합니다.
1. 캡처한 창을 **바요엔-스타**와 같은 색의 크로마키로 설정합니다.
1. 캡처한 창의 제목표시줄을 잘라줍니다. 30픽셀만 잘라주세요!

    _위쪽 영역을 더 자르게 되면 점수판이 잘리게 됩니다. 이 외의 다른 꾸미기는 자유롭게 해주세요!_
1. 끝났습니다!

OBS와 XSplit를 사용하고 계시다면 아래의 설명에 따라하시면 됩니다!

- OBS (Open Broadcaster Software) 캡쳐 및 크로마키 설정
    1. 메인화면을 송출창에 추가합니다.<br/>
        - **소스 목록 > 윈도우 캡쳐 > 윈도우 '[bayoen-star.exe]: bayoen-star'**
    1. **'바요엔-스타-캡처'**나 마음에 드는 이름으로 바꿔줍니다.
    1. **'바요엔-스타-캡처'**에 크로마키를 설정합니다.<br/>
        - **우클릭 > 필터 > + > 크로마 키 > 키 색상 형식 > '바요엔-스타'의 크로마키와 같은 색**
    1. **'바요엔-스타-캡처'**의 제목표시줄을 잘라줍니다.<br/>
        - **우클릭 > 변환 > 변환 편집 > 자르기 > 위 > 30 픽셀**
    1. 끝났습니다! **'바요엔-스타-캡처'**를 원하는 크기로 원하는 곳에 두면 됩니다!

    _*OBS 윈도우 캡쳐에서 '윈도우 일치 우선순위'는 '창 제목이 일치해야 합니다'로 해주시는게 좋습니다!_

<p align="center">
    <img src="{{ site.lang_url }}/res/obs-chromakey-example-1.png" class="box" width="48%" alt="obs-chromakey-example-1"/>
    <img src="{{ site.lang_url }}/res/obs-chromakey-example-2.png" class="box" width="48%" alt="obs-chromakey-example-2"/>
    <br/><span><strong>OBS</strong> 캡처 및 크로마키 설정 적용</span>
    <br/><span>오버레이가 아닌 메인 창을 캡처하셔야 합니다!</span>
</p>

- XSplit 캡처 및 크로마키 설정
    1. 메인화면을 송출창에 추가합니다.<br/>
        - **소스 추가 > Screen 캡쳐 > 윈도우 캡쳐 'bayoen-star' (bayoen-star.exe)**
    1. **'바요엔-스타-캡처'**나 마음에 드는 이름으로 바꿔줍니다.
    1. **'바요엔-스타-캡처'**에 크로마키를 설정합니다.<br/>
        - **설정 > 색 > 키 > 크로마키 > '바요엔-스타'의 크로마키와 같은 색**
    1. **'바요엔-스타-캡처'**의 제목표시줄을 잘라줍니다.<br/>
        - **설정 > 레이아웃 > 사진/삽화의 불필요한 부분 다듬기 > 상단 > 39 포인트**
    1. 끝났습니다! **'바요엔-스타-캡처'**를 원하는 크기로 원하는 곳에 두면 됩니다!

<p align="center">
    <img src="{{ site.lang_url }}/res/xsplit-chromakey-example-1.png" class="box" width="48%" alt="xsplit-chromakey-example-1"/>
    <img src="{{ site.lang_url }}/res/xsplit-chromakey-example-2.png" class="box" width="48%" alt="xsplit-chromakey-example-2"/>
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

## 세부 설정



<p align="center">
    <img src="{{ site.lang_url }}/res/bayoen-star-settings-streaming-ko.png" class="box" alt="bayoen-star-settings-streaming"/>
    <br/><span>인터넷 방송을 위한 <strong>바요엔-스타</strong>의 메뉴</span>
</p>

1. **항상 위에**: 체크하면 **바요엔-스타**를 항상 위로 둡니다
2. **자동 숨기기**: 체크하면 게임 중이 (**'Working'** 상태) 아닐 때, 점수판을 숨깁니다
3. **텍스트 출력**: 체크하면 텍스트 파일로 결과를 출력합니다
4. **점수판 크기조절**: 체크하면 점수판의 크기를 최대크기로 고정합니다.
5. **크로마키 설정**: 여러가지 크로마키를 설정할 수 있습니다

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

<p align="center">
    <!-- <img src="/bayoen-star/bayoen-star-example-goal-total-none.png" width="70%" alt="bayoen-star-example"/><br/> -->
    <img src="/bayoen-star/bayoen-star-example-chroma.png" width="70%" alt="bayoen-star-example-chroma"/><br/>
    <img src="/bayoen-star/bayoen-star-example-goal-first-blue.png" width="70%" alt="bayoen-star-example-goal-first-blue"/><br/>
    <!-- <img src="/bayoen-star/bayoen-star-example-ingame.png" width="70%" alt="bayoen-star-example-ingame"/> -->
</p>
**'bayoen-star'** also supports several tools for streamming with Puyo Puyo Tetris.

- 텍스트출력: 점수판 대신 직접 인터페이스를 구성하고 싶을 때 유용한 기능입니다. 송출프로그램에서 텍스트파일 (\*.txt) 파일을 불러올 수 있습니다. '**메인창 > Menu > Settings > MAIN > Export Texts**'을 체크하면 오른쪽의 '**Folder**' 경로에 파일이 저장됩니다.


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