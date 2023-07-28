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

# Invalid IPv6

If you're stuck on connection to master server and when you're pinging `api.battlebit.cloud` and it resolves as Invalid IPv6, do next:

<details>

<summary>Windows 10</summary>

1. Click on "Network & Internet" in Windows Settings.

<img src="../.gitbook/assets/network.png" alt="" data-size="original">

2. Select Ethernet tab and click on "Change adapter options".

<img src="../.gitbook/assets/adapter.png" alt="" data-size="original">

3. Right click on your main adapter and select properties.

<img src="../.gitbook/assets/adapterproperties.png" alt="" data-size="original">

4. Disable "Internet Protocol Version 6 (TCP/IPv6)" and press OK.

<img src="../.gitbook/assets/disableipv6.png" alt="" data-size="original">

</details>

<details>

<summary>Windows 11</summary>

WIP

</details>
