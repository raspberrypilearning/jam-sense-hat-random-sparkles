## 반복문 추가하기

프로그램을 계속 다시 실행하기보단, 반복문을 추가하여 계속 프로그램이 진행되도록 할 수 있습니다.

--- task ---

먼저 파일 상단에 `import`을 추가합니다.

```python
from time import sleep
```

이를 사용하여 픽셀 배치 중간에 프로그램을 일시 중지합니다.

--- /task ---

--- task ---

`while True :`를 코드에 추가하여 random, `set_pixel` 및 `sleep` 가 모두 반복문 내에 있도록 합니다.

```python
while True:
    x = randint(0, 7)
    y = randint(0, 7)
    r = randint(0, 255)
    g = randint(0, 255)
    b = randint(0, 255)
    sense.set_pixel(x, y, r, g, b)
    sleep(0.1)
```

--- /task ---

--- task ---

코드를 실행하면 무작위로 반짝이는 것을 볼 수 있습니다!

--- /task ---

--- task ---

일시 중지 시간을 더 짧게 변경해보십시오.

--- /task ---
