---
description: >-
  ACCESS_VIOLATION - 處理程序試圖在禁止/無法存取的記憶體區塊中寫入
---

# 🔘 應用程式無法正確啟動 (The application was unable to start correctly) (0xc0000005)

<figure><img src="../.gitbook/assets/0xc0000005.jpg" alt=""><figcaption></figcaption></figure>

1. 如果你有使用第三方防毒軟體，請確保它並未干擾遊戲運行，並將BattleBit與EAC的檔案資料夾加入防毒軟體的白名單。如果問題持續，將該防毒軟體刪除 (尤其是趨勢科技Trend Micro)
2. 試著以系統管理員身分執行 `BattlebitEAC.exe` or `EasyAntiCheat.exe`。

<figure><img src="../.gitbook/assets/browse.png" alt="" width="374"><figcaption><p>Steam遊戲庫中右鍵點選遊戲，點選管理，再點選瀏覽本機檔案。</p></figcaption></figure>

<figure><img src="../.gitbook/assets/runasadmin.png" alt="" width="287"><figcaption><p>選取遊戲的exe檔後按右鍵並選取「以系統管理員身分執行」。</p></figcaption></figure>

3. [執行 sfc/dism](../other/running-sfc-dism.md).
4. 停用任何超頻 (overclocking) 軟體。
5. 驗證遊戲檔按。

<figure><img src="../.gitbook/assets/BBR_Validation.gif" alt=""><figcaption><p>Steam遊戲庫中右鍵點選遊戲並選取「內容」，選取「已安裝的檔案」分頁並點選「驗證遊戲檔案的完整性」。.</p></figcaption></figure>

6. 將遊戲重新安裝至其他硬碟。
