## set_pixel 사용하기

우선 임의의 숫자를 생각해놓고 `set_pixel`함수를 이용해서 임의의 색상을 Sense HAT 화면의 임의의 위치에 표시합니다.

--- task ---

Raspberry Pi를 사용하는 경우 **Mu** 을 열어 시작합니다. 웹 에뮬레이터를 사용하는 경우, 시작하기 전에 예제 코드를 삭제하십시오.

--- /task ---

--- task ---

새 파일에 Sense Hat 모듈을 import 합니다.

실제 Sense HAT 또는 Trinket 에뮬레이터를 사용하는 경우 import 행은 다음과 같습니다.

```python
from sense_hat import SenseHat
```

데스크탑 에뮬레이터를 사용하는 경우 import 행은 다음과 같습니다.

```python
from sense_emu import SenseHat
```

나머지 코드는 모든 버전에서 동일합니다.

--- /task ---

--- task ---

다음, 아래를 추가하여 Sense HAT에 연결합니다:

```python
sense = SenseHat()
```

--- /task ---

--- task ---

이제 0에서 7 사이의 난수를 생각하여 변수 `x`에 할당합니다. 예를 들면 다음과 같습니다:

```python
x = 4
```

--- /task ---

--- task ---

0에서 7 사이의 다른 난수를 생각한 다음 `y`에 할당합니다.

```python
y = 5
```

--- /task ---

--- task ---

0에서 255 사이의 세 개의 난수를 생각한 다음 `r`, `g`, `b`에 각각 할당합니다.

```python
r = 19
g = 180
b = 230
```

--- /task ---

--- task ---

자 이제 `set_pixel`함수를 사용해서 여러분이 임의로 정한 위치에 여러분이 임의로 정한 색을 설정합니다.

```python
sense.set_pixel(x, y, r, g, b)
```

--- /task ---

--- task ---

이제 **Run** 버튼으로 코드를 실행합니다. 한 픽셀에 불이 들어온 것을 볼 수 있습니다.

--- /task ---

--- task ---

이제 난수를 다시 변경하고 프로그램을 다시 실행하십시오. 두 번째 픽셀에 불이 들어옵니다!

--- /task ---
