# [Mobile] 無RWD網頁於手持裝置載入時呈現沒有符合螢幕寬度

於手持裝置上，若網頁無設置RWD以原大小呈現時，螢幕需用手指內縮網頁才會變成符合螢幕寬度。

## 解決方法

於載入或翻轉手持裝置時設置viewport的width，一般預設為`width=device-width`，當網頁無RWD效果以一般大小呈現時，需將width設為最低media query支援的width。

請注意: 需拿掉`initial-scale=1.0`設定才有作用。
