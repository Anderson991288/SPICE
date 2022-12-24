# LTspice
## 如何引入新的MOS model到LTspice

### 1.在https://ptm.asu.edu/  選擇你要用的model

![156](https://user-images.githubusercontent.com/68816726/178109151-7e2dcd11-b0fe-48d1-b2e6-39a2a914b334.png)

### 2.把整個library  file複製到記事本並存成.pm檔

![螢幕擷取畫面 2022-07-09 223237](https://user-images.githubusercontent.com/68816726/178110241-3be2893e-d8ba-468b-917d-0a391dc4ade6.png)

### 3.把.pm放入以下路徑

![123](https://user-images.githubusercontent.com/68816726/178109112-9979033c-a507-4e67-95a2-121a5e86fda0.png)

### 4.接個簡單的電路測試一下

![螢幕擷取畫面 2022-07-09 221123](https://user-images.githubusercontent.com/68816726/178109469-72b0f2f1-5f45-4741-8b44-a8c415635a6e.png)
![螢幕擷取畫面 2022-07-09 221255](https://user-images.githubusercontent.com/68816726/178109519-ae62738b-906e-488a-8ce8-14d0ac6186e5.png)

### 5.MOS上右鍵輸入參數

![156456](https://user-images.githubusercontent.com/68816726/178110098-c2bef8de-91d9-47ea-be47-cbdae0473ac6.png)


### 6.點選右上方的.op圖示，在這裡輸入".include 檔名"

Ex:
```
.include 16nm.pm
```
![螢幕擷取畫面 2022-07-09 221531](https://user-images.githubusercontent.com/68816726/178109731-a3e867a3-392e-47b3-90e9-7baec404923a.png)

### 7.完成模擬

![螢幕擷取畫面 2022-07-09 222035](https://user-images.githubusercontent.com/68816726/178109821-81c4f0e2-dac2-4373-aff3-66215a378e4b.png)
