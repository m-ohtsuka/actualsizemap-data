# オーガスタ・ナショナル 外形データの出典

このファイルは `tools/build_data.py build augusta-national` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | アメリカ ジョージア州オーガスタ（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap way [871993734](https://www.openstreetmap.org/way/871993734)（Augusta National Golf Club）版 17（wayの最終更新 2026-03-25T14:44:36Z） |
| OSMのタグ | `addr:city=Augusta`、`addr:housenumber=2604`、`addr:postcode=30904`、`addr:state=GA`、`addr:street=Washington Road`、`leisure=golf_course`、`name=Augusta National Golf Club`、`name:ja=オーガスタ・ナショナル・ゴルフクラブ`、`operator=Augusta National Inc.`、`phone=+1-706-667-6000`、`website=https://www.masters.com`、`wikidata=Q765780`、`wikipedia=en:Augusta National Golf Club` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/871993734/full.json` |
| 取得時刻（UTC） | 2026-11-14T02:25:57Z |
| 外形の範囲 | クラブの敷地の境界（パー3コース・練習場などを含む） |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 49（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 5.091 km |
| 隣接点の最大間隔 | 529.8 m |
| 基準点 | 緯度 33.5009509、経度 -82.0228502（正距円筒型の局所平面に投影した外接矩形の中心） |
| 細部 | なし |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |
