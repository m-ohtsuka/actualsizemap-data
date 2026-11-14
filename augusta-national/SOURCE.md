# オーガスタ・ナショナル 外形データの出典

このファイルは `tools/build_data.py build augusta-national` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | アメリカ ジョージア州オーガスタ（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap way [871993734](https://www.openstreetmap.org/way/871993734)（Augusta National Golf Club）版 17（wayの最終更新 2026-03-25T14:44:36Z） |
| OSMのタグ | `addr:city=Augusta`、`addr:housenumber=2604`、`addr:postcode=30904`、`addr:state=GA`、`addr:street=Washington Road`、`leisure=golf_course`、`name=Augusta National Golf Club`、`name:ja=オーガスタ・ナショナル・ゴルフクラブ`、`operator=Augusta National Inc.`、`phone=+1-706-667-6000`、`website=https://www.masters.com`、`wikidata=Q765780`、`wikipedia=en:Augusta National Golf Club` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/871993734/full.json` |
| 取得時刻（UTC） | 2026-11-14T03:30:48Z |
| 外形の範囲 | クラブの敷地の境界（パー3コース・練習場などを含む） |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 49（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 5.091 km |
| 隣接点の最大間隔 | 529.8 m |
| 基準点 | 緯度 33.5009509、経度 -82.0228502（正距円筒型の局所平面に投影した外接矩形の中心） |
| 細部 | 36本。輪郭の内側の形が分かるwayを、1本ずつ並び順のまま線にした。つなぎ合わせ・簡略化・直線補完はしていない。上の取得方法と同じく、wayごとに OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/<way ID>/full.json` で取得した（取得時刻は下の表）。番号を出す細部（18本）には、OSMの`ref`をそのまま番号（`ref`）として書き出した |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 細部（並び順）

| 名前 | way ID | 版 | 形 | 点数 | 取得時刻（UTC） | OSMのタグ |
|---|---|---|---|---|---|---|
| 1番ホール | [854913181](https://www.openstreetmap.org/way/854913181) | 7 | 閉じていない線 | 3 | 2026-11-14T03:30:49Z | `description=Augusta Hole 1`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=9`、`name=Tea Olive`、`par=4`、`ref=1` |
| 1番グリーン | [1381014610](https://www.openstreetmap.org/way/1381014610) | 2 | 閉じた線 | 68 | 2026-11-14T03:30:50Z | `description=Hole 1 green`、`golf=green`、`ref=1` |
| 2番ホール | [854915607](https://www.openstreetmap.org/way/854915607) | 9 | 閉じていない線 | 4 | 2026-11-14T03:30:51Z | `description=Augusta Hole 2`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=1`、`name=Pink Dogwood`、`par=5`、`ref=2` |
| 2番グリーン | [1381016958](https://www.openstreetmap.org/way/1381016958) | 2 | 閉じた線 | 77 | 2026-11-14T03:30:51Z | `description=Hole 2 green`、`golf=green`、`ref=2` |
| 3番ホール | [854940639](https://www.openstreetmap.org/way/854940639) | 7 | 閉じていない線 | 3 | 2026-11-14T03:30:52Z | `description=Augusta Hole 3`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=13`、`name=Flowering Peach`、`par=4`、`ref=3` |
| 3番グリーン | [1381017712](https://www.openstreetmap.org/way/1381017712) | 2 | 閉じた線 | 67 | 2026-11-14T03:30:53Z | `description=Hole 3 green`、`golf=green`、`ref=3` |
| 4番ホール | [854940645](https://www.openstreetmap.org/way/854940645) | 8 | 閉じていない線 | 3 | 2026-11-14T03:30:54Z | `description=Augusta Hole 4`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=15`、`name=Flowering Crab Apple`、`par=3`、`ref=4` |
| 4番グリーン | [1381032393](https://www.openstreetmap.org/way/1381032393) | 2 | 閉じた線 | 76 | 2026-11-14T03:30:55Z | `description=Hole 4 green`、`golf=green`、`ref=4` |
| 5番ホール | [854940652](https://www.openstreetmap.org/way/854940652) | 8 | 閉じていない線 | 4 | 2026-11-14T03:30:56Z | `description=Augusta Hole 5`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=5`、`name=Magnolia`、`par=4`、`ref=5` |
| 5番グリーン | [1381032394](https://www.openstreetmap.org/way/1381032394) | 2 | 閉じた線 | 56 | 2026-11-14T03:30:57Z | `description=Hole 5 green`、`golf=green`、`ref=5` |
| 6番ホール | [854940657](https://www.openstreetmap.org/way/854940657) | 8 | 閉じていない線 | 3 | 2026-11-14T03:30:57Z | `description=Augusta Hole 6`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=17`、`name=Juniper`、`par=3`、`ref=6` |
| 6番グリーン | [1381249779](https://www.openstreetmap.org/way/1381249779) | 2 | 閉じた線 | 74 | 2026-11-14T03:30:58Z | `description=Hole 6 green`、`golf=green`、`ref=6` |
| 7番ホール | [854949697](https://www.openstreetmap.org/way/854949697) | 8 | 閉じていない線 | 3 | 2026-11-14T03:30:59Z | `description=Augusta Hole 7`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=11`、`name=Pampas`、`par=4`、`ref=7` |
| 7番グリーン | [1381255369](https://www.openstreetmap.org/way/1381255369) | 2 | 閉じた線 | 68 | 2026-11-14T03:31:00Z | `description=Hole 7 green`、`golf=green`、`ref=7` |
| 8番ホール | [855188617](https://www.openstreetmap.org/way/855188617) | 11 | 閉じていない線 | 4 | 2026-11-14T03:31:01Z | `description=Augusta Hole 8`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=3`、`name=Yellow Jasmine`、`par=5`、`ref=8` |
| 8番グリーン | [1381255370](https://www.openstreetmap.org/way/1381255370) | 2 | 閉じた線 | 65 | 2026-11-14T03:31:02Z | `description=Hole 8 green`、`golf=green`、`ref=8` |
| 9番ホール | [854913182](https://www.openstreetmap.org/way/854913182) | 8 | 閉じていない線 | 3 | 2026-11-14T03:31:03Z | `description=Augusta Hole 9`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=7`、`name=Carolina Cherry`、`par=4`、`ref=9` |
| 9番グリーン | [1381257293](https://www.openstreetmap.org/way/1381257293) | 2 | 閉じた線 | 60 | 2026-11-14T03:31:04Z | `description=Hole 9 green`、`golf=green`、`ref=9` |
| 10番ホール | [855188624](https://www.openstreetmap.org/way/855188624) | 10 | 閉じていない線 | 3 | 2026-11-14T03:31:04Z | `description=Augusta Hole 10`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=6`、`name=Camellia`、`par=4`、`ref=10` |
| 10番グリーン | [930486859](https://www.openstreetmap.org/way/930486859) | 5 | 閉じた線 | 53 | 2026-11-14T03:31:05Z | `description=Hole 10 green`、`golf=green`、`landuse=grass`、`ref=10`、`surface=grass` |
| 11番ホール | [855657864](https://www.openstreetmap.org/way/855657864) | 9 | 閉じていない線 | 3 | 2026-11-14T03:31:06Z | `description=Augusta Hole 11`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=8`、`name=White Dogwood`、`par=4`、`ref=11` |
| 11番グリーン | [930486860](https://www.openstreetmap.org/way/930486860) | 5 | 閉じた線 | 61 | 2026-11-14T03:31:07Z | `description=Hole 11 green`、`golf=green`、`landuse=grass`、`ref=11`、`surface=grass` |
| 12番ホール | [855657869](https://www.openstreetmap.org/way/855657869) | 6 | 閉じていない線 | 2 | 2026-11-14T03:31:08Z | `description=Augusta Hole 12`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=16`、`name=Golden Bell`、`par=3`、`ref=12` |
| 12番グリーン | [1381269202](https://www.openstreetmap.org/way/1381269202) | 2 | 閉じた線 | 69 | 2026-11-14T03:31:09Z | `description=Hole 12 green`、`golf=green`、`ref=12` |
| 13番ホール | [855657881](https://www.openstreetmap.org/way/855657881) | 9 | 閉じていない線 | 4 | 2026-11-14T03:31:10Z | `description=Augusta Hole 13`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=4`、`name=Azalea`、`par=5`、`ref=13` |
| 13番グリーン | [1381274335](https://www.openstreetmap.org/way/1381274335) | 2 | 閉じた線 | 83 | 2026-11-14T03:31:10Z | `description=Hole 13 green`、`golf=green`、`ref=13` |
| 14番ホール | [855658985](https://www.openstreetmap.org/way/855658985) | 7 | 閉じていない線 | 4 | 2026-11-14T03:31:12Z | `description=Augusta Hole 14`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=12`、`name=Chinese Fir`、`par=4`、`ref=14` |
| 14番グリーン | [1381277116](https://www.openstreetmap.org/way/1381277116) | 2 | 閉じた線 | 70 | 2026-11-14T03:31:12Z | `description=Hole 14 green`、`golf=green`、`ref=14` |
| 15番ホール | [856563246](https://www.openstreetmap.org/way/856563246) | 12 | 閉じていない線 | 3 | 2026-11-14T03:31:13Z | `description=Augusta Hole 15`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=2`、`name=Firethorn`、`par=5`、`ref=15` |
| 15番グリーン | [1381280718](https://www.openstreetmap.org/way/1381280718) | 2 | 閉じた線 | 79 | 2026-11-14T03:31:14Z | `description=Hole 15 green`、`golf=green`、`ref=15` |
| 16番ホール | [856563253](https://www.openstreetmap.org/way/856563253) | 7 | 閉じていない線 | 3 | 2026-11-14T03:31:15Z | `description=Augusta Hole 16`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=18`、`name=Redbud`、`par=3`、`ref=16` |
| 16番グリーン | [930491137](https://www.openstreetmap.org/way/930491137) | 7 | 閉じた線 | 74 | 2026-11-14T03:31:16Z | `description=Hole 16 green`、`golf=green`、`landuse=grass`、`ref=16`、`surface=grass` |
| 17番ホール | [856563261](https://www.openstreetmap.org/way/856563261) | 7 | 閉じていない線 | 3 | 2026-11-14T03:31:16Z | `description=Augusta Hole 17`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=14`、`name=Nandina`、`par=4`、`ref=17` |
| 17番グリーン | [1381289043](https://www.openstreetmap.org/way/1381289043) | 2 | 閉じた線 | 97 | 2026-11-14T03:31:17Z | `description=Hole 17 green`、`golf=green`、`ref=17` |
| 18番ホール | [856563268](https://www.openstreetmap.org/way/856563268) | 12 | 閉じていない線 | 4 | 2026-11-14T03:31:18Z | `description=Augusta Hole 18`、`golf=hole`、`golf:course:name=Augusta National`、`handicap=10`、`name=Holly`、`par=4`、`ref=18` |
| 18番グリーン | [1381289719](https://www.openstreetmap.org/way/1381289719) | 2 | 閉じた線 | 74 | 2026-11-14T03:31:19Z | `description=Hole 18 green`、`golf=green`、`ref=18` |
