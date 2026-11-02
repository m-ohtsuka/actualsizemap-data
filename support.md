---
title: 実寸マップ サポート
---

# 実寸マップ サポート

iOSアプリ「実寸マップ」のサポートページです。

## このアプリについて
山手線の線路の形や、大山古墳・大濠公園・東京ドームの外形などを「物差し」にして、地図の上の別の場所に、その場所の地図と同じ縮尺で重ねるアプリです。長さを決めた円と直線も重ねられます。

## よくある質問

### 物差しの大きさは、どのくらい正確ですか？
物差しは、表示している場所の地図の縮尺に合わせて描きます。表示の中心が北緯・南緯60°以内で、物差しの中心から20km以内であれば、距離の誤差が1%以内になるように作っています。大きさを比べるための目安で、測量には使えません。北緯・南緯60°より極に近い場所では、画面の上に「精度保証範囲外」と出ます。

### 「現在地へ」を押しても移りません
端末の「設定」アプリで、「実寸マップ」の位置情報の利用を許可してください。位置情報は「現在地へ」を押したときだけ使い、どこにも送りません。

### 通信できないときも使えますか？
物差しはアプリに入っているので、通信がなくても表示できます。背景の地図と場所の検索には通信が要ります。

### 物差しのデータはどこから来ていますか？
OpenStreetMapのデータから作っています（© OpenStreetMap contributors）。データは、このリポジトリでODbLのもとで公開しています。出典と加工の内容は、各物差しのフォルダの`SOURCE.md`と、アプリの情報画面にあります。

### 物差しを増やしてほしい
ご要望は、下のお問い合わせからお寄せください。

## お問い合わせ
不具合のご報告やご要望は、メール（[psi-median.1x@icloud.com](mailto:psi-median.1x@icloud.com)）でお寄せください。

## プライバシー
[プライバシーポリシー](privacy.html)をご覧ください。

---

# ActualSizeMap Support

ActualSizeMap overlays familiar shapes — the Yamanote line, Daisen Kofun, Ohori Park, Tokyo Dome, and circles and lines of a chosen length — on any place on the map, at the same ground scale as the map there.

- **Accuracy.** Within 60° N/S of the equator and within 20 km of a ruler's center, the app is designed to keep distance errors within 1%. It is meant for comparison, not for surveying.
- **Location.** If "現在地へ" (current location) does not work, allow location access for the app in the Settings app. Location is used only when you tap the button and is never sent anywhere.
- **Offline.** Rulers are bundled with the app and work offline; background maps and place search need a network connection.
- **Data.** Ruler shapes are derived from OpenStreetMap (© OpenStreetMap contributors) and published in this repository under the ODbL.
- **Contact.** Please report bugs or send requests by email to [psi-median.1x@icloud.com](mailto:psi-median.1x@icloud.com). See also the [privacy policy](privacy.html).
