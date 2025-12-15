# 讓 H81M-E/B85M-G/B85M-PLUS-BM6AF 主機板可以使用 i5-4xxx or i7-4xxx
For some Asus i3-4xxx mb can not boot while upgrade CPU to i5-4xxx or i7-4xxx, here is the way to do the trick.

1. 用可以開機的 CPU，進行安裝 Win10 (或 Win7)

2. 下載 「01-B85M-H81M 認識 i7-4790.zip】，並解壓縮。

3. 安裝 ME 更新工具 MEI_Win7-8-8-1_VER95151730 (只能是這個版本，其他版都無法正常運作)

4. 利用 BIOS_updater_for_New_4th_Gen_Intel_Core_Processors 內的 update.exe 安裝 <br>
  3-1. H81M-E 主機板，安裝 H81M-E-ASUS-3602.CAP <br>
  3-2. B85M-G 主機板，安裝 B85M-G-ASUS-3602.CAP <br>
  3-3. B85M-PLUS-BM6AF 主機板，安裝 B85M-PLUS-ASUS-BM6AF-2001.CAP <br>
  就會順便更新 Data.BIN 這個讓 MB 認識 i5-4460 與 i7-4790 的資料檔。
