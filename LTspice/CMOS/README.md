# tsmc 180 nm CMOS Inverter
## import model from https://sanjayvidhyadharan.in/Downloads/

### 1.將	cmosn.asy  cmosp.asy 貼到記事本中存到 C:\Users\Documents\LTspiceXVII\lib\sym

### 2.將 tsmc018.lib 貼到記事本中存到 C:\Users\Documents\LTspiceXVII\lib\sub

### 3.開啟LTspice，點選右上方.op輸入:
```
.include .include tsmc018.lib
```
### 4.接好電路如下

![123](https://user-images.githubusercontent.com/68816726/178129609-1c3cfb13-da94-48cf-b32c-c1081d64553a.png)

### 5.Vin Vout 曲線

![image](https://user-images.githubusercontent.com/68816726/178129650-9cfa12d0-110c-4b1e-88b4-7a405a384642.png)
