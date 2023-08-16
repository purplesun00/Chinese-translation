---
description: 錯誤的解析度設定造成遊戲停止。
---

# 🔘 解析度錯誤

本頁面旨在幫助曾手動調整至某特定遊戲解析度，導致BattlebBit於載入時一再停止運行的玩家。 請依下列步驟修復:

1. 開啟Appdata資料夾。

<figure><img src="../.gitbook/assets/run_menu_appdata.png" alt=""><figcaption><p>按 Windows+R, 輸入 <code>%appdata%</code> 後按 Enter.</p></figcaption></figure>

2. 找到 `BattleBitConfig.ini` 檔案並打開。

<figure><img src="../.gitbook/assets/appdata_folder_config_file.png" alt=""><figcaption><p>AppData/Roaming 資料夾</p></figcaption></figure>

3. &#x20;將 `customresolution` 設為 true ，並將 `customscreenresolution` 設為你的螢幕解析度:

<figure><img src="../.gitbook/assets/config_file.png" alt=""><figcaption><p>BattleBit config 設定檔</p></figcaption></figure>

4. &#x20;存檔並將檔案關閉。
