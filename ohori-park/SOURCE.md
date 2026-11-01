# 大濠公園 外形データの出典

このファイルは `tools/build_data.py build ohori-park` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-01 |
| 場所の説明 | 福岡県福岡市（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap way [23344558](https://www.openstreetmap.org/way/23344558)（大濠公園）版 20（wayの最終更新 2025-02-08T11:30:58Z） |
| OSMのタグ | `addr:block_number=1番`、`addr:city=福岡市`、`addr:housenumber=2`、`addr:postcode=810-0051`、`addr:province=福岡県`、`addr:quarter=大濠公園`、`addr:suburb=中央区`、`architect=本多静六;永見健一`、`architect:wikidata=Q11520098;Q11550338`、`contact:phone=+81 92-741-2004`、`contact:tripadvisor=1423813`、`contact:website=https://www.ohorikouen.jp/`、`fee=no`、`leisure=park`、`name=大濠公園`、`name:en=Ōhori Park`、`name:fr=Parc Ōhori`、`name:ja-Hira=おおほりこうえん`、`name:ja-Latn=Ōhori-kōen`、`name:ko=오호리 공원`、`opening_hours=24/7`、`operator=西鉄グループ公園管理団体`、`start_date=1929-03`、`wikidata=Q846710`、`wikimedia_commons=Category:Ohori Park`、`wikipedia=ja:大濠公園` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/23344558/full.json` |
| 取得時刻（UTC） | 2026-11-01T06:38:34Z |
| 外形の範囲 | 公園の境界（大濠池と、池を囲む園地） |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 47（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 2.798 km |
| 隣接点の最大間隔 | 205.6 m |
| 基準点 | 緯度 33.5861331、経度 130.3768351（正距円筒型の局所平面に投影した外接矩形の中心） |
| 細部 | 9本。輪郭の内側の形が分かるwayを、1本ずつ並び順のまま線にした。つなぎ合わせ・簡略化・直線補完はしていない。上の取得方法と同じく、wayごとに OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/<way ID>/full.json` で取得した（取得時刻は下の表） |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 細部（並び順）

| 名前 | way ID | 版 | 形 | 点数 | 取得時刻（UTC） | OSMのタグ |
|---|---|---|---|---|---|---|
| 池の外周 | [33041300](https://www.openstreetmap.org/way/33041300) | 7 | 閉じた線 | 134 | 2026-11-01T06:38:35Z |  |
| 鴨島 | [493424051](https://www.openstreetmap.org/way/493424051) | 6 | 閉じた線 | 20 | 2026-11-01T06:38:36Z | `leaf_type=broadleaved`、`name=鴨島`、`name:en=Duck Island`、`name:fr=Île des Canards`、`name:ja-Hira=かもじま`、`name:ja-Latn=Kamo-jima`、`place=islet` |
| 菖蒲島 | [23303818](https://www.openstreetmap.org/way/23303818) | 13 | 閉じた線 | 47 | 2026-11-01T06:38:37Z | `leaf_type=needleleaved`、`name=菖蒲島`、`name:en=Sweet Flag Island`、`name:fr=Île des Iris`、`name:ja-Hira=しょうぶじま`、`name:ja-Latn=Shōbu-jima`、`natural=wood`、`place=islet` |
| 柳島 | [507524049](https://www.openstreetmap.org/way/507524049) | 5 | 閉じた線 | 52 | 2026-11-01T06:38:38Z | `leaf_type=needleleaved`、`name=柳島`、`name:en=Willow Island`、`name:fr=Île des Saules`、`name:ja-Hira=やなぎしま`、`name:ja-Latn=Yanagi-shima`、`natural=wood`、`place=islet` |
| 松島 | [493424054](https://www.openstreetmap.org/way/493424054) | 6 | 閉じた線 | 85 | 2026-11-01T06:38:39Z | `leaf_type=needleleaved`、`name=松島`、`name:en=Pinus Island`、`name:fr=Île des Pins`、`name:ja-Hira=まつしま`、`name:ja-Latn=Matsu-shima`、`natural=wood`、`place=islet` |
| 観月橋 | [33041302](https://www.openstreetmap.org/way/33041302) | 5 | 閉じていない線 | 3 | 2026-11-01T06:38:40Z | `bridge=yes`、`highway=footway`、`layer=1`、`lit=no`、`name=観月橋`、`name:en=Moon Viewing Bridge`、`name:fr=Pont d'observation de la Lune`、`name:ja-Hira=かんげつきょう`、`name:ja-Latn=Kangetsu-kyō`、`surface=paving_stones` |
| 皐月橋 | [33041297](https://www.openstreetmap.org/way/33041297) | 6 | 閉じていない線 | 4 | 2026-11-01T06:38:40Z | `bridge=yes`、`highway=footway`、`layer=1`、`lit=yes`、`name=皐月橋`、`name:en=Satsuki Bridge`、`name:fr=Pont Satsuki`、`name:ja-Hira=さつき ばし`、`name:ja-Latn=Satsuki-bashi`、`surface=sett` |
| 松月橋 | [506725967](https://www.openstreetmap.org/way/506725967) | 6 | 閉じていない線 | 2 | 2026-11-01T06:38:41Z | `bridge=yes`、`highway=footway`、`layer=1`、`lit=yes`、`name=松月橋`、`name:en=Shōgetsu Bridge`、`name:fr=Pont Shōgetsu`、`name:ja-Hira=しょうげつ ばし`、`name:ja-Latn=Shōgetsu-bashi`、`surface=sett` |
| 茶村橋 | [493424052](https://www.openstreetmap.org/way/493424052) | 6 | 閉じていない線 | 2 | 2026-11-01T06:38:42Z | `bridge=yes`、`description=改修により、「ちゃそんばし」の名称が明記されています。`、`highway=footway`、`layer=1`、`lit=yes`、`name=茶村橋`、`name:en=Chason Bridge`、`name:fr=Pont du village de thé`、`name:ja-Hira=ちゃそん ばし`、`name:ja-Latn=Chason-bashi`、`surface=sand` |
