# 「宇治金時」Rime 配色主題/skin/theme

<img align=right src="https://raw.githubusercontent.com/GJRobert/rime-theme-uji_kintoki/master/screenshot.png">

## 發想
> 宇治金時（うじきんとき）是一種日本的傳統刨冰，以日式抹茶加砂糖及水煮成糖漿，淋在刨冰上，旁邊加上以砂糖熬煮的紅豆，製成色彩分明的甜品。也有人加上白色的糯米糰子，增加色彩及口感。

（[宇治金時 - Wikiwand](https://www.wikiwand.com/zh-tw/宇治金時)）

![可口的宇治金時〜:D](https://upload.wikimedia.org/wikipedia/commons/thumb/6/60/Kakigoori.jpg/320px-Kakigoori.jpg)

很久以前，ghsrobert 使用一個叫 TiddlySpace 的筆記網站（另一個很長的故事），偶然在新建一個重要的 space 時，系統產生了一個有紅、有綠、有藍的 color scheme，用久了感覺就像宇治金時一樣，越看越讓人覺得舒服（其他自動產生的顏色主題通常會偏同一色系居多，不像這個主題的視覺感受這麼豐富）。於是這色盤就陪伴主人下來，不僅可以用在 Alfred 上，還可以用在 Rime 上！

## 安裝
1) 執行 [東風破](https://github.com/rime/plum) 的 `rime-install` 命令安裝以下配方：

```bash
$ bash rime-install GJRobert/rime-theme-uji_kintoki
```

2a) 若為 Windows 小狼毫：

```bash
$ bash rime-install GJRobert/rime-theme-uji_kintoki:customize:frontend=weasel
```

2b) 若為 macOS 鼠鬚管：

```bash
$ bash rime-install GJRobert/rime-theme-uji_kintoki:customize:frontend=squirrel
```

3) 最後在 weasel.custom.yaml 或 squirrel.custom.yaml 中，將 `style/color_scheme:` 改為 `uji_kintoki`

## 相容性
鼠鬚管及小狼毫應該均可正常使用，但目前只有在鼠鬚管上測試過。

小狼毫好像有一些鼠鬚管所沒有的介面設定項目，該部分目前尚無研究，所以對於小狼毫而言可能還有可以再改進/細膩設定之處。歡迎 fork 自行設定/分享/回饋。

## 姐妹作
本版為原味，若愛淺色，亦可參考[淡版](https://github.com/GJRobert/rime-theme-uji_kintoki_light)。

## 銘謝
* Rime 專案所有貢獻者
* 「Rime 西米」產生器（[小狼毫用](https://bennyyip.github.io/Rime-See-Me/)/[鼠鬚管用](https://gjrobert.github.io/Rime-See-Me-squirrel/)）加速調色過程
* 自動安裝部署之做法係參考 [lotem/rime-theme-windows10](https://github.com/lotem/rime-theme-windows10)，感謝 Lotem
* MacDown
