# actualsizemap-data

iOSアプリ「実寸マップ（ActualSizeMap）」に同梱しているデータの配布用リポジトリ。

OpenStreetMapから抽出・加工した物差し（路線の線形と、建造物などの外形。順序付きWGS84座標のGeoJSON）と、その出典・加工内容を置く。アプリ本体のソースコードは含まない。

## 内容
- `catalog.json` — データ一式の版（`dataVersion`）と、物差しの一覧（並び順）
- `yamanote/yamanote.geojson` — 山手線の環状経路一周分（内回り・外回りの片方）と基準点、駅の位置
- `daisen-kofun/daisen-kofun.geojson` — 大山古墳（大仙古墳）の外形（3重の濠を含む外周）と基準点、細部（墳丘・1重目の濠の外縁）
- `ohori-park/ohori-park.geojson` — 大濠公園の外形（公園の境界）と基準点、細部（池の外周・島・橋）
- `tokyo-dome/tokyo-dome.geojson` — 東京ドームの外形（建物の外形）と基準点
- 各ディレクトリの `SOURCE.md` — 取得日、OSMのrelation/way IDと版、取得時刻、取得方法、加工内容、基準点（路線は採用方向と駅、外形は細部の一覧も）
- `privacy.md` — アプリのプライバシーポリシー（[GitHub Pagesで公開](https://m-ohtsuka.github.io/actualsizemap-data/privacy.html)）
- `support.md` — アプリのサポートページ（[GitHub Pagesで公開](https://m-ohtsuka.github.io/actualsizemap-data/support.html)）

アプリに同梱した版と同じものを、データ一式の版ごとにタグ（`data-YYYYMMDD`）を付けて公開する。アプリの情報画面からは、同梱版と同名のタグへリンクする。タグは付け替えない。`yamanote-YYYYMMDD` のタグは、山手線だけを配っていたころの版。

## ライセンス
© OpenStreetMap contributors

このリポジトリのデータは [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/) の下で提供される。詳細は [LICENSE.md](LICENSE.md) と [OpenStreetMap: Copyright and License](https://www.openstreetmap.org/copyright) を参照。

プライバシーポリシー（`privacy.md`）とサポートページ（`support.md`）はデータではなく、ODbLの対象ではない。
