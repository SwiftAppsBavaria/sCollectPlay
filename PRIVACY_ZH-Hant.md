# sCollectPlay 和 sCollectPlay Lite 隱私權政策

更新日期：2026-10-23

## 摘要

sCollectPlay 和 sCollectPlay Lite **不會**蒐集、儲存或傳送任何個人資料。這兩個 App 只在你的 Mac 或 Windows 電腦上運作。沒有帳號，沒有雲端連線，沒有分析服務，也沒有廣告。

## App 處理哪些資料

App 只讀取你明確交給它的那些資料夾裡的媒體檔案 —— 透過在開啟對話框中選擇：一個要掃描的資料夾、
一個 iTunes 或 Apple Music XML，或者一個 sCollect 媒體庫。讀取的是檔名、檔案大小、日期和檔案的
中繼資料，對於 XML 或媒體庫，還包括其中的目錄資訊。

沒有你的選擇，App 不會存取任何檔案。macOS 透過 App 沙箱來確保這一點。

## App 在你的 Mac 上放了什麼

- **設定與視窗位置**，位於 App 受保護的專屬資料夾中。
- **macOS 的許可，讓 App 下次啟動時能重新開啟你的資料夾。** 儲存的是資料夾路徑，不是檔案內容。
  只有這樣，App 才不必每次啟動都重新詢問。
- **sCollectPlay 另外還會儲存：** 最近使用的資料夾、XML 檔案和媒體庫的清單，你自建的播放清單，
  排序方式以及直欄瀏覽器的狀態 —— 同樣位於 App 受保護的專屬資料夾中。

只要你刪除 App，這些內容也就一併消失。

## 兩項可能引起疑問的權限

**網路存取權限。** App 之所以申請它，是因為沒有這項權限時 macOS 會把內建的說明視窗顯示為空白
—— 說明是由一個需要該權限的系統元件呈現的，即使它只載入程式本身的檔案。App 自己**不會連向
網際網路上的任何位址**，不下載任何東西，也不回報任何東西。

位於網路磁碟（SMB、NFS）上的資料夾，App 是透過你 Mac 的檔案系統存取的，而不是透過自己的
連線。

**控制 Apple Music。** 當你把一個選擇作為播放清單傳送到 Apple Music 時，App 會用產生的播放清單
開啟 Apple Music，並可依你的意願取代那裡已有的同名播放清單。為此 macOS 需要你的同意，並會在
第一次時詢問。除此之外，App 不會控制任何其他程式。

## 你的檔案

App 不寫入標籤，也不更改你檔案的中繼資料。

當你開啟一個 sCollect 媒體庫時，App 會把你的評分和播放次數（含日期和時間）儲存到該媒體庫資料夾中的 `rueckmeldungen.json` 檔案裡，以便 sCollect 接收這些資訊。App 不會更改媒體庫本身和媒體檔案，這些資訊也不會離開你的電腦。

只有當你明確刪除某個檔案時，App 才會把它移到 macOS 的垃圾桶，並將其從清單中移除；如果它來自
某個 sCollect 媒體庫，該媒體庫的目錄也會相應更新。在沒有垃圾桶的磁碟上，App 會先詢問是否
要永久刪除該檔案。

## 在 Windows 上

以上內容說明的是 Mac。在 Windows 上，sCollectPlay 和 sCollectPlay Lite 只把以下內容儲存在本機、App 自己的資料夾中
（`%LOCALAPPDATA%\Packages\<套件>\LocalState` 和 `Settings`）：

- **設定與視窗位置。**
- **最近一次選擇的來源** —— 掃描過的資料夾、一個 iTunes XML 檔案或一個 sCollect 媒體庫 —— 以及上一次掃描的結果。
- **媒體庫在 Mac 上的資料夾與你電腦上資料夾的對應關係**（僅資料夾路徑）。
- **sCollectPlay 另外還會儲存：** 你自建的播放清單、最近使用的資料夾、XML 檔案和媒體庫的清單、排序方式以及
  分欄瀏覽器的狀態。
- **錯誤記錄**（`fehler.log`），它只留在你的電腦上。

解除安裝 App 時，這些內容會全部刪除。

App 只在你選擇的位置讀取媒體檔案和 XML 檔案；sCollect 媒體庫只會被讀取（「你的檔案」中所述的 `rueckmeldungen.json` 檔案除外）。App 不會自行建立網路連線，不使用分析服務，
也沒有廣告。Windows 本身無法播放的檔案，會交給該檔案類型的預設程式，預設程式由你在 Windows 中選擇。

在 sCollectPlay 中為 VLC 或裝置匯出播放清單時，App 會把其中的檔案拷貝到你選擇的資料夾。在 Windows 上，App
不會刪除媒體檔案。

## Microsoft Store

在 Windows 上，購買（sCollectPlay）、下載和更新都透過 Microsoft Store 進行，適用 Microsoft 的隱私權聲明。
sCollectPlay Lite 是免費的，並會提及完整版。

## 不轉交，不分析

沒有廣告，沒有分析服務，沒有傳給第三方的當機報告，也沒有帳號。

## 聯絡方式

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
