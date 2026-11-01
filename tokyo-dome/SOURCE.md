# 東京ドーム 外形データの出典

このファイルは `tools/build_data.py build tokyo-dome` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-01 |
| 場所の説明 | 東京都文京区（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap way [20028328](https://www.openstreetmap.org/way/20028328)（東京ドーム）版 43（wayの最終更新 2026-01-01T07:04:58Z） |
| OSMのタグ | `addr:block_number=3`、`addr:city=文京区`、`addr:housenumber=61`、`addr:neighbourhood=後楽一丁目`、`addr:postcode=112-0004`、`addr:province=東京都`、`building=yes`、`leisure=stadium`、`lit=yes`、`name=東京ドーム`、`name:en=Tokyo Dome`、`name:es=Tokyo Dome`、`name:fr=Tokyo Dome`、`name:ja=東京ドーム`、`name:ru=Стадион Токио Доум`、`name:zh=東京巨蛋`、`sport=baseball;multi`、`wikidata=Q733748`、`wikipedia=ja:東京ドーム` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/20028328/full.json` |
| 取得時刻（UTC） | 2026-11-01T15:14:01Z |
| 外形の範囲 | 建物の外形（屋根の縁） |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 47（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 0.720 km |
| 隣接点の最大間隔 | 39.3 m |
| 基準点 | 緯度 35.7055141、経度 139.7519654（正距円筒型の局所平面に投影した外接矩形の中心） |
| 細部 | なし |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |
