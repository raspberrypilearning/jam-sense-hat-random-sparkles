## set_pixel का उपयोग करना

First, you'll think up some random numbers and use the `set_pixel` function to place a random colour on a random location on the Sense HAT display.

\--- task \---

If you're using a Raspberry Pi, open **Mu** to start. यदि आप वेब एमुलेटर का उपयोग कर रहे हैं, तो शुरू होने से पहले उदाहरण कोड हटाएं।

\--- /task \---

\--- task \---

नई फ़ाइल में, Sense HAT मॉड्यूल आयात करके शुरू करें।

यदि आप वास्तविक Sense HAT या Trinket एमुलेटर का उपयोग कर रहे हैं, तो आयात लाइन है:

```python
from sense_hat import SenseHat
```

यदि आप डेस्कटॉप एमुलेटर का प्रयोग कर रहे हैं, तो आयात लाइन है:

```python
from sense_emu import SenseHat
```

बाकी कोड सभी संस्करणों के लिए समान होगा।

\--- /task \---

\--- task \---

इसके बाद, Sense HAT से एक कनेक्शन बनाएं:

```python
sense = SenseHat()
```

\--- /task \---

\--- task \---

अब 0 और 7 के बीच एक यादृच्छिक संख्या सोचे और उसे परिवर्तनीय `x` के बराबर कर दे, उदाहरण के लिए:

```python
x = 4
```

\--- /task \---

\--- task \---

0 और 7 के बीच एक और यादृच्छिक संख्या के बारे सोचे और उसे परिवर्तनीय `y` के बराबर कर दे:

```python
y = 5
```

\--- /task \---

\--- task \---

0 और 255 के बीच तीन यादृच्छिक संख्याओं के बारे सोचे और उन्हें परिवर्तनीय `r`, `b` और `g` के बराबर कर दे:

```python
r = 19
g = 180
b = 230
```

\--- /task \---

\--- task \---

अब `set_pixel` फ़ंक्शन का उपयोग आपके यादृच्छिक स्थान पर अपना यादृच्छिक रंग रखने के लिए करें:

```python
sense.set_pixel(x, y, r, g, b)
```

\--- /task \---

\--- task \---

Now run your code by the **Run** button. आपको एक पिक्सेल जलता हुआ दिखेगा।

\--- /task \---

\--- task \---

अब कुछ नयी यादृच्छिक संख्या चुनें - उन्हें बदल दें - और फिर से प्रोग्राम को चलाएं। प्रदर्शन पर एक दूसरा पिक्सेल दिखाई देना चाहिए!

\--- /task \---