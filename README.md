# DS-123
# 簡介
## 任務一
### 說明題目
讀入一份檔案，內容包含OID、arrival、duration、timeout，請依照arrival(到達時間)，為排序依據由小至大，若arrival相同，則以OID為依據。接著將結果輸出至sorted file，同時print 工作內容與程式執行時間到螢幕上。 
## 任務二
### 說明題目
依據任務一的sorted file，模擬cpu序列進行分類到abortjob和donejob中再計算成功率和平均delay，最後再輸入進output file中。

## 版本紀錄
v1中有基本的任務一二功能

v2則擴充了雙重CPU的功能

merge sort version 則是取代原本的shell sort加速排序進程。

上圖是shell sort，下圖是merge ，總體加速了7 clock


![image](https://github.com/Kevin171717/DS-/assets/140044307/baa0d30c-e96a-4551-b1f7-4872391b879f)

![image](https://github.com/Kevin171717/DS-/assets/140044307/10e6242b-afdc-4cf2-ac3b-d124a5acd49d)


main則是把merge sort 與quick sort 合在一起



![image](https://github.com/Kevin171717/DS-/assets/140044307/f46dac63-9a2f-403a-af36-e8c471460ffb)

有趣的是quick 的時間反而是最長的
