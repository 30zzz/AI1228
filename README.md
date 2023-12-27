# 人工智慧期末報告-天氣預報的時間序列預測
11124227陳姿吟 11124228黃丞語 11124206施彥愷
## 準備資料
●可使用之Colab帳號

●馬克斯普朗克生物地球化學研究所記錄的耶拿氣候資料集
## 實際操作
## 1 導入和設定

<img width="212" alt="1" src="https://github.com/30zzz/AI1228/assets/113405753/bade69d0-d9ff-4fd7-9e05-a216e9fd228f">

<img width="520" alt="2" src="https://github.com/30zzz/AI1228/assets/113405753/c0182065-0e37-4c48-9080-8d3791bf1d04">

## 2 數據可視化

為了讓我們了解我們正在使用的數據，每個特徵都繪製在下面。這顯示了 2009 年至 2016 年期間每個特徵的獨特模式。它還顯示了存在異常的位置，這些異常將在標準化過程中得到解決。

<img width="508" alt="3" src="https://github.com/30zzz/AI1228/assets/113405753/d1b460fb-61da-4721-9276-2c4c2edac535">

<img width="512" alt="4" src="https://github.com/30zzz/AI1228/assets/113405753/b5c83d40-af8a-4481-9cda-da84b2b77d19">

## 3 資料預處理

此模型顯示前 5 天的數據，即每小時採樣一次的 720 個觀測值。72（12小時*每小時6次）觀測後的溫度將作為標籤。

<img width="308" alt="5" src="https://github.com/30zzz/AI1228/assets/113405753/eb60ba7e-1553-4527-9342-1dbccc57b62c">

<img width="409" alt="6" src="https://github.com/30zzz/AI1228/assets/113405753/7d422d3e-fc85-4dde-9b5d-c7e1e4d46af2">
