# cool640zmk

![](img/img00001.jpg)

![](img/img00002.jpg)


## What is cool640zmk?

cool640zmk is ortholiner keyboard.

<br>
cool640zmk use seeed xiao ble,run zmk_firmware.
<br>
<br>

作った理由
<br>
https://sizu.me/m_ki/posts/m2cfnik4z2xd
<br>

## firmware

[zmk-config](https://github.com/telzo2000/zmk-config-cool640zmk)

<br>
keymap editor

https://nickcoutsos.github.io/keymap-editor/

<br>
zmk studio

https://zmk.studio/

<br>

自作キーボードへのzmk_firmwareのインストールについて

https://sizu.me/m_ki/posts/kvixkn2mec6a

<br>
zmk_firmwareでのキーマップ編集について

https://sizu.me/m_ki/posts/m3devs7be5km

<br>

## buildguide

https://github.com/telzo2000/cool640zmk/blob/main/buildguide_for_cool640zmk.md

（執筆前）
<br>




<br>


## BOM
<b>common parts</b>
| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|番号|名前|数|備考|調達先|参考価格（送料込）|<br>
|1|PCB|1||[elecrow](https://www.elecrow.com)<br>[JLCPCB](https://jlcpcb.com)<br>[ALLPCB](https://www.allpcb.com)||<br>
|2|Top case|1|3D Print|||
|3|Bottom case|1|3D Print|||
|4|Switch knob|1|3D Print|||
|5|Slide switch<br>スライドスイッチ|1||[秋月電子](https://akizukidenshi.com/catalog/g/g115370/)|１個30円|
|6|AAAA Battery case<br>単４電池ケース|2||[秋月電子](https://akizukidenshi.com/catalog/g/g102670/)|１個40円|
|7|XIAO nRF52840|1|MCU Board|[seeed studio](https://jp.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html?msclkid=5541f7f3d0f911eca6023fe520de5bfa)<br>[秋月電子](https://akizukidenshi.com/catalog/g/g117341/)|1940円|
|8|Diode<br>ダイオード|40|SMD|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|100個で220円程度から|
|9|Switch socket<br>スイッチソケット|40|choc|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|10個で165円程度|
|10|Screw<br>ネジ|2|黒色、スリムヘッドM2 4mm|[遊舎工房](https://shop.yushakobo.jp/products/a0800s2?variant=37665432535201)|50本880円(遊舎工房)|
|11|Screw<br>ネジ|2|M2 4mm|DIY shop|10本200円程度|
|12|Spacer<br>スペーサー|2|M2 10mm|DIY shop|10本400円程度|
|13|Keyswitch<br>キースイッチ|40|chocV1及びV2対応|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)|１個100程度|
|14|Keycap<br>キーキャップ|40|16.8mm以下の狭ピッチ、ロープロが最適|3D Print||

In addition, NiHM rechargeable batteries (4 AAA size), USB cable, etc. are required.
<br>
この他に、NiHM充電池（単４形４本）、USBケーブル等が必要です。
<br>
狭ピッチのキーキャップについては、次のサイトを利用して作成し、3Dプリンタで印刷しました。

[Maker World](https://makerworld.com/ja/makerlab/parametricModelMaker?designId=1378891&exp=1746523152&from=model_page&key=d50b80e9ac74e47d2eedbaa7d961abea&modelName=keycap_generator_rev.scad&scadUrl=https%3A%2F%2Fmakerworld.bblmw.com%2Fmakerworld%2Fmodel%2FUS196180b5aa4a8f%2Fmsfile%2F2025-05-06_a1b411b65c3a.scad%3Fat%3D1746522852&uid=432320066&unikey=127d3f10-1090-486f-b41f-f75099af80c4)




# license

[CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)

![](img/by-nc-sa.png)
