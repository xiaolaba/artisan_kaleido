# artisan_kaleido
old copy with center 309 temperature recorder, the master source code evolved, this is apply to old version only artisan-2.4.6  

download , https://github.com/artisan-roaster-scope/artisan/archive/refs/tags/v2.4.6.zip  


#kaleido 咖啡炒豆機, 咖啡烘焙機, 改機套用 IoT, 從此變成低 [智能], 其實有些用途但是開發方便而已, 用BLE 模擬串口變成無線連結, 不需要實體USB線, 普通用家還真沒興趣玩這個.  

最近調整一下, 快速搜尋, 用家自行 IoT 套用 ESP8266 或者 ESP32 是可以的, 模組也開賣了. 手邊有 ESP32 直接換掉, 其實還是有用的. 不會自己改機的也可以透過代理升級舊型號增加 IoT 功能, 有手動能力的喜歡玩樂自己改機也可以.   

Artisan 開源的要自己加入模組或者寫交互機制也是可以. 用 MAX6675/33835直接MCU是最小體積最低成本的方案, 開發烘烤曲線用 Centre-309 外接溫度計, 從此備用, 不再主力.  
last version  

artisan-2.4.6\artisan-2.4.6\src\comm\CommCENTER309Python3.py  

改機紀錄, Artisan的主事者以把更新過的舊的通訊資料納入, 更容易讀取或適合用家修改, 但是這個溫度計現在賣US$200, 比起 ESP32 USD$2 來說高很多, 只好放棄不再繼續使用.  
https://github.com/artisan-roaster-scope/artisan/pull/552  
https://github.com/artisan-roaster-scope/artisan/issues/127  
