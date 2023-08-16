---
cover: ../.gitbook/assets/ipv6timeout.png
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🔘 無效的IPv6 (Invalid IPv6)

如果你卡在連線至主伺服器頁面，而ping `api.battlebit.cloud` 回傳的結果為無效的IPv6 (Invalid IPv6)，請依系統版本進行以下步驟:

<details>

<summary>Windows 10</summary>

1. 於系統設定中點選 「網路與網際網路」。

<img src="../.gitbook/assets/network.png" alt="" data-size="original">

2. 依你的連線種類選擇Wifi或乙太網路，並選擇「變更介面卡選項」。

<img src="../.gitbook/assets/adapter.png" alt="" data-size="original">

3. 右鍵點選你使用的介面卡，並點選內容。

<img src="../.gitbook/assets/adapterproperties.png" alt="" data-size="original">

5. 將 「網際網路通訊協定第6版 (TCP/IPv6)」取消勾選，並點選確定。

<img src="../.gitbook/assets/disableipv6.png" alt="" data-size="original">

</details>

<details>

<summary>Windows 11</summary>

1. 於系統設定中點選 「網路與網際網路」。

<img src="https://images.taylorgibbs.dev/bkfhsk.png" alt="" data-size="original">

2. 點選「進階網路設定」。

<img src="https://images.taylorgibbs.dev/uzyc3u.png" alt="" data-size="original">

3. 向下滑並點選「更多網路介面卡選項」

<img src="https://images.taylorgibbs.dev/a2myev.png" alt="" data-size="original">

4. 右鍵點選你使用的介面卡，並點選內容。

<img src="https://images.taylorgibbs.dev/rn04y5.png" alt="" data-size="original">

4. 將 「網際網路通訊協定第6版 (TCP/IPv6)」取消勾選，並點選確定。

<img src="https://images.taylorgibbs.dev/no8q11.png" alt="" data-size="original">

</details>
