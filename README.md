# Cell_GPS_track_MQTT<br>
track cell GPS with MQTT<br><br>
手機端程式:<br>
1.GPSrecord.aia 使用mit app inventos 2 開啟<br>
2.下載必須DeviceFingerprint: Uniquely identify devices 擴充<br>
3.下載必須UrsAI2PahoMqtt 擴充<br>
4.下載必須MyService 擴充<br>
5.填入你的MQTT broker url 以及帳號密碼<br>
6.編譯並由cell phone下載<br>
7.執行並確定權限開啟後按下start開始記錄GPS軌跡<br><br>
網頁監控端<br>
1.開啟gpsMQTTmap.html並找到MQTT的broker填入要連接的MQTT伺服器位址以及使用者帳號密碼<br>
2.找一個webserver將gpsMQTTmap.html置入<br>
3.由電腦端或手機端開啟webserver的gpsMQTTmap.html<br>
4.gpsMQTTmap.html將會實時接收有執行GPSrecord的GSP位址並在畫面地圖上顯示最後位置及移動軌跡<br>

