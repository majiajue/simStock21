# simStock 小確幸股票模擬機
小確幸下載台灣上市股票歷史成交價格，設計策略及買賣規則，模擬買賣及評估報酬率。

發佈的版本：([release](https://github.com/peiyu66/simStock21/releases))

## 策略規則
   小確幸的策略是短期投機買賣：
1. 低買高賣賺取價差優先於賺股息股利。
1. 縮短買賣週期（最短2天），優先於提升報酬率。
1. 保本小賺維持現金流，優先於投機大賺。
1. 操作要簡單不要複雜，只做多不做空。

## 買賣規則
1. 每次買進只使用現金的三分之一，即「起始本金」及兩次加碼本金。
1. 買進時一次買足起始本金可買到的數量。
1. 可自動模擬2次加碼。
1. 賣時一次全部賣出結清。

### 誰適合使用小確幸？
✐✐✐ [小確幸適性評估](https://docs.google.com/forms/d/e/1FAIpQLSdzNyfMl5NP1sCSHSxoSCWqqdeAPSQbw4kAiwlCv0pzJkjgrg/viewform?usp=sf_link) ✐✐✐

### 小確幸沒有在App Store上架？
* App Store自2017年已不允許「個人」開發者上架含有「模擬賭博」內容的App。
* 小確幸下載的即時及歷史股價雖然是公開資料，若想上架卻應取得來源網站的許可。

### 如何安裝小確幸ipa？
* 若有加入Apple Developer，就自己在Xcode直接建造直接安裝。
* 不然只好向作者登記iPhone或iPad的序號作為開發機，就可從release的[itms-services](itms-services://?action=download-manifest&url=https://github.com/peiyu66/simStock21/releases/download/v0.2(5)/manifest.plist)連結下載安裝。

### 有些股票找不到？
* 只有上市股票才能被搜尋到，故不能找到上櫃股票。
* 如果股票已經在股群之內，就不會重複列在搜尋結果。

### 如何買賣？
小確幸自動模擬買賣行動，你不能決定什麼時候買多少、什麼時候賣多少。但你可以就模擬結果使用日期左側的圓形按鈕，更改其買賣時機。
