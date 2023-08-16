---
description: >-
  Game crashes instantly if launched from Steam, but runs fine if launched from
  executables in installed files.
cover: ../.gitbook/assets/launchfromsteam.png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🔘 從Steam啟動EAC

1. 在Steam遊戲庫中右鍵點選遊戲並點選「內容」。

<figure><img src="../.gitbook/assets/properties.png" alt=""><figcaption></figcaption></figure>

2. 將下列 (如果你的遊戲檔案路徑與此不同請使用實際路徑) 在啟動選項中貼上: \
   `"C:\Program Files (x86)\Steam\steamapps\common\BattleBit Remastered\EasyAntiCheat.exe" %command%`&#x20;

<figure><img src="../.gitbook/assets/launchoptionsfix.png" alt=""><figcaption><p>看起來應該要這樣。如果你的遊戲檔案路徑與此不同，請以實際的路徑取代。</p></figcaption></figure>
