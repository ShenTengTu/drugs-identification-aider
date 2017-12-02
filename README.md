# 雲端技術輔助毒品鑑識之研究
使用 `APP Inventor 2` 及 `Google Fusion Tables API` 來輔助毒品鑑識的工作。

## Google Fusion Tables資料欄位
- 級別
- 中文學名
- 英文學名
- 俗名 : 需要用英文逗號`,`分隔不同的俗名
- 形狀 : 需要用英文逗號`,`分隔不同的形狀
- 顏色
- 氣味
- 備註
- 濫用方式 : 需要用英文逗號`,`分隔不同的濫用方式
- 症狀
- 圖片路徑 : 使用網路連結。

## Google Fusion Tables API
- 將預先建立好的CSV檔匯入至`Google Fusion Tables`。
- `Google Fusion Tables`將存在"帳戶持有者"的雲端硬碟，可以線上編輯並能管理檔案的存取權限。
- 使用Fusion Tables API  通過RESTful HTTP請求獲取特定的資料。
- 透過`APP Inventor 2`的`FusionTablesControl`使手機能及時更新資料至本地資料庫
