# Cell_GPS_track_MQTT
track cell GPS with MQTT
手機端程式:
1.GPSrecord.aia 使用mit app inventos 2 開啟
2.下載必須DeviceFingerprint: Uniquely identify devices 擴充
3.下載必須UrsAI2PahoMqtt 擴充
4.下載必須MyService 擴充
5.填入你的MQTT broker url 以及帳號密碼
6.編譯並由cell phone下載
7.執行並確定權限開啟後按下start開始記錄GPS軌跡
網頁監控端
1.開啟gpsMQTTmap.html並找到MQTT的broker填入要連接的MQTT伺服器位址以及使用者帳號密碼
2.找一個webserver將gpsMQTTmap.html置入
3.由電腦端或手機端開啟webserver的gpsMQTTmap.html
4.gpsMQTTmap.html將會實時接收有執行GPSrecord的GSP位址並在畫面地圖上顯示最後位置及移動軌跡

