## 소개

여러분의 Sense HAT을 자랑스럽게 반짝여보세요.

--- collapse ---
---
title: 준비물
---

- Raspberry Pi
- Sense Hat

    Mu를 설치해야합니다. 터미널 창을 열고 다음 명령어를 입력하세요:

    ```bash
    sudo apt install mu-editor
    ```

또는:

- PC

Raspberry Pi는 있지만 Sense HAT이 없는 경우 Raspbian에서 Sense HAT 에뮬레이터를 사용할 수 있습니다. 코드 상단의 import 행을 다음과 같이 변경하기만 하면 됩니다:

`from sense_hat import SenseHat`

을 다음과 같이 변경하세요

`from sense_emu import SenseHat`.

Raspberry Pi가없는 경우 [trinket.io/sense-hat](https://trinket.io/sense-hat)에서 온라인으로 Trinket Sense HAT 에뮬레이터를 사용할 수 있습니다. import 행은 동일합니다.

--- /collapse ---

--- collapse ---
---
title: 배우게 될 것
---

- Sense HAT의 컬러 LED 제어
- RGB 색
- 반복문
- 랜덤

--- /collapse ---

--- no-print ---

--- collapse ---
---
title: Jam 관계자를 위한 정보
---

이 프로젝트를 인쇄해야 하는 경우 [PDF 버전](https://github.com/raspberrypilearning/jam-worksheets/raw/master/pdf/Sense-HAT-Random-Sparkles.pdf)을 사용할 수 있습니다. 인쇄하기 전에 이 페이지의 참고 사항을 준수하십시오.

--- /collapse ---

--- /no-print ---
