# Study-room-reservation-system
## IOT實務專題 圖書自習室預約系統

#### YouTube Demo：<https://youtu.be/bDGpoSbZxr4>
----

#### 嗨! 柏洋 承轅，一起維護這些code跟版面吧!

此作品使用HTML、CSS、JavaScript撰寫座位預約介面，搭配Node-red與後端Node.js Express伺服器進行連接，並透過OM2M與感測器進行溝通。實現一個簡易的圖書自習室預約系統。
使用者可透過網頁登入，查看當前座位狀態，針對可預約的座位進行預約，或是透過每個座位上所擺放的RFID 感應器，經由刷卡來現場預約座位。

座位預約畫面
![reservation01](https://user-images.githubusercontent.com/68801780/128376646-47f12b19-7d5e-49c6-91c0-5def6d1edab8.png)



#### *需自行搭建Node-Red及Om2m環境*

#### *網頁端*
1. 將 web_flows.json 匯入至 Node-Red
2. 開啟Node-Red dashboard 並複製URL
3. 修改Webpage/public/logintest.html檔案的window.location = "步驟2的URL"
4. 啟動OM2M
5. 開啟logintest.html開始預約

#### *感測器端*
1. 將 sensor_flows.json 匯入至 Node-Red
2. 待新增...
