# 大濠公園 外形データの出典

このファイルは `tools/build_data.py build ohori-park` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-01 |
| 出典 | OpenStreetMap way [23344558](https://www.openstreetmap.org/way/23344558)（大濠公園）版 20（wayの最終更新 2025-02-08T11:30:58Z） |
| OSMのタグ | `addr:block_number=1番`、`addr:city=福岡市`、`addr:housenumber=2`、`addr:postcode=810-0051`、`addr:province=福岡県`、`addr:quarter=大濠公園`、`addr:suburb=中央区`、`architect=本多静六;永見健一`、`architect:wikidata=Q11520098;Q11550338`、`contact:phone=+81 92-741-2004`、`contact:tripadvisor=1423813`、`contact:website=https://www.ohorikouen.jp/`、`fee=no`、`leisure=park`、`name=大濠公園`、`name:en=Ōhori Park`、`name:fr=Parc Ōhori`、`name:ja-Hira=おおほりこうえん`、`name:ja-Latn=Ōhori-kōen`、`name:ko=오호리 공원`、`opening_hours=24/7`、`operator=西鉄グループ公園管理団体`、`start_date=1929-03`、`wikidata=Q846710`、`wikimedia_commons=Category:Ohori Park`、`wikipedia=ja:大濠公園` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/23344558/full.json` |
| 取得時刻（UTC） | 2026-11-01T04:31:20Z |
| 外形の範囲 | 公園の境界（大濠池と、池を囲む園地） |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 47（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 2.798 km |
| 隣接点の最大間隔 | 205.6 m |
| 基準点 | 緯度 33.5861331、経度 130.3768351（正距円筒型の局所平面に投影した外接矩形の中心） |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |
