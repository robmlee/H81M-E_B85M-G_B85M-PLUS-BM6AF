# 讓 ASUS H81M-E/B85M-G/B85M-PLUS-BM6AF 主機板，可以升級使用 i5-4xxx or i7-4xxx CPU
**For some Asus i3-4xxx mb can not boot while upgrade CPU to i5-4xxx or i7-4xxx, here is the way to do the trick.**

#### 注意：本網站內容僅供參考，不保證其準確性與完整性。使用者應自行承擔使用本網站資訊的風險，我們不對任何直接或間接的損失負責。<br><br>

## A. 步驟說明:
- 1). 經測試，當 CPU 升級為 i7-4xxx，PSU(電源供應器)瓦數為 300 瓦時，電腦還是會無法啟動！而當改用 500 瓦時，電腦就能順利啟動了！

- 2). 用可以開機的 CPU，進行安裝 Win10 (或 Win7) <br><br>

- 3). 下載三個檔案，並解壓縮。
  - 3-1. BIOS_updater_for_New_4th_Gen_Intel_Core_Processors.zip (或從 Asus 官網的 H81M-E for **Win7** 驅動程式及工具程式/BIOS公用程式 [自行下載](https://www.asus.com/tw/supportonly/h81me/helpdesk_download/) ) 
  - 3-2. H81M-E_B85M-G_B85M-PLUS-BM6AF.zip (或是從 Asus 官網自行下載各 MB 的最後一版 BIOS 檔)
  - 3-3. 從 Asus 官網的 H81M-E for **Win7** 驅動程式及工具程式/晶片組，下載 [Management Engine Interface V9.5.15.1730 for Windows Win7 64bit & Win8 64bit & Win8.1 64bit---(WHQL)](https://www.asus.com/tw/supportonly/h81me/helpdesk_download/) <br><br>

- 4). 安裝 ME 更新工具 MEI_Win7-8-8-1_VER95151730 (只能是這個版本，其他版都無法正常運作。  The only version that works!) <br><br>

- 5). 利用 BIOS_updater_for_New_4th_Gen_Intel_Core_Processors 內的 update.exe 安裝將以下 bios 安裝一次： <br>
  - 5-1. H81M-E 主機板，安裝 H81M-E-ASUS-3602.CAP <br>
  - 5-2. B85M-G 主機板，安裝 B85M-G-ASUS-3602.CAP <br>
  - 5-3. B85M-PLUS-BM6AF 主機板，安裝 B85M-PLUS-ASUS-BM6AF-2001.CAP <br>
  
  安裝過程，就會順便將 Data.BIN 這個檔，更新到 MB 上，讓 MB 認識 i5-4460 與 i7-4790 的資料檔。
<br><br>

## B. 特別說明(含免責聲明)：
- 本處所提供的檔案，都是下載自 Asus 官網，
- 適用範圍：本內容僅供參考，不構成專業建議。
- 資訊準確性：我們不保證資訊的準確、完整或可靠性，使用者需自行判斷。
- 風險自負：使用本網站資訊所產生的任何損失或損害，由使用者自行承擔。
- 責任限制：不對因使用網站或連結網站內容造成的任何損失負責。

