# actualsizemap-data

iOSアプリ「実寸マップ（ActualSizeMap）」に同梱している路線データの配布用リポジトリ。

OpenStreetMapから抽出・加工した山手線の線形（順序付きWGS84座標のGeoJSON）と、その出典・加工内容を置く。アプリ本体のソースコードは含まない。

## 内容
- `yamanote/yamanote.geojson` — 山手線の環状経路一周分（内回り・外回りの片方）と基準点
- `yamanote/SOURCE.md` — 取得日、OSMのrelation/way IDと版または取得時刻、取得方法、採用方向、加工内容、基準点

アプリに同梱した版と同じものを、版ごとにタグ（`yamanote-YYYYMMDD`）を付けて公開する。アプリの情報画面からは、同梱版と同名のタグへリンクする。タグは付け替えない。

## ライセンス
© OpenStreetMap contributors

このリポジトリのデータは [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/) の下で提供される。詳細は [LICENSE.md](LICENSE.md) と [OpenStreetMap: Copyright and License](https://www.openstreetmap.org/copyright) を参照。
