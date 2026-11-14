# 名城線 線形データの出典

このファイルは `tools/build_data.py build meijo` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | 愛知県名古屋市（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap relation [1905460](https://www.openstreetmap.org/relation/1905460)（名古屋市営名城線 (右回り)）版 29（relationの最終更新 2026-05-30T13:00:10Z） |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/relation/1905460/full.json` |
| 取得時刻（UTC） | 2026-11-14T14:45:21Z |
| 採用方向 | 右回り（片方向のみ。もう一方の方向・並行線・留置線は含めない） |
| 加工内容 | relationの経路メンバー（role ""）のwayを接続順に並べ、向きを揃えて1本の閉じた折れ線にした。隣接wayの共有端点の重複を除いた。簡略化・直線補完はしていない |
| 点数 | 394（先頭と末尾は同一点） |
| 全長（WGS84測地線） | 26.401 km（relationに distance タグが無いため、全長は照合していない） |
| 隣接点の最大間隔 | 462.3 m |
| 基準点 | 緯度 35.1567259、経度 136.9331919（正距円筒型の局所平面に投影した外接矩形の中心） |
| 駅 | 28駅。relationの stop メンバー（停車位置のノード）を並び順に使い、重複（起点と終点）は1つにした。どの駅も線形の点列に含まれ、点列の中の順序が駅の並びと同じであることを確かめた |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 経路を構成するway（接続順）

| # | way ID | 版 |
|---|---|---|
| 1 | [858723262](https://www.openstreetmap.org/way/858723262) | 2 |
| 2 | [32163968](https://www.openstreetmap.org/way/32163968) | 18 |
| 3 | [884327659](https://www.openstreetmap.org/way/884327659) | 4 |
| 4 | [32164002](https://www.openstreetmap.org/way/32164002) | 12 |
| 5 | [1523844274](https://www.openstreetmap.org/way/1523844274) | 1 |
| 6 | [1523844273](https://www.openstreetmap.org/way/1523844273) | 1 |
| 7 | [32165173](https://www.openstreetmap.org/way/32165173) | 14 |
| 8 | [962753468](https://www.openstreetmap.org/way/962753468) | 2 |
| 9 | [32165183](https://www.openstreetmap.org/way/32165183) | 28 |
| 10 | [1374996101](https://www.openstreetmap.org/way/1374996101) | 1 |

## 駅（並び順）

| # | 駅名 | node ID | 版 |
|---|---|---|---|
| 1 | 金山 | [5214024836](https://www.openstreetmap.org/node/5214024836) | 12 |
| 2 | 東別院 | [361009845](https://www.openstreetmap.org/node/361009845) | 13 |
| 3 | 上前津 | [361009886](https://www.openstreetmap.org/node/361009886) | 14 |
| 4 | 矢場町 | [361009882](https://www.openstreetmap.org/node/361009882) | 13 |
| 5 | 栄 | [361009814](https://www.openstreetmap.org/node/361009814) | 13 |
| 6 | 久屋大通 | [361009795](https://www.openstreetmap.org/node/361009795) | 14 |
| 7 | 名古屋城 | [361009807](https://www.openstreetmap.org/node/361009807) | 16 |
| 8 | 名城公園 | [361009789](https://www.openstreetmap.org/node/361009789) | 13 |
| 9 | 黒川 | [361009792](https://www.openstreetmap.org/node/361009792) | 15 |
| 10 | 志賀本通 | [361009828](https://www.openstreetmap.org/node/361009828) | 12 |
| 11 | 平安通 | [361009803](https://www.openstreetmap.org/node/361009803) | 11 |
| 12 | 大曽根 | [361009826](https://www.openstreetmap.org/node/361009826) | 21 |
| 13 | ナゴヤドーム前矢田 | [361011236](https://www.openstreetmap.org/node/361011236) | 15 |
| 14 | 砂田橋 | [361011199](https://www.openstreetmap.org/node/361011199) | 13 |
| 15 | 茶屋ヶ坂 | [361011197](https://www.openstreetmap.org/node/361011197) | 15 |
| 16 | 自由ヶ丘 | [361011086](https://www.openstreetmap.org/node/361011086) | 14 |
| 17 | 本山 | [361011167](https://www.openstreetmap.org/node/361011167) | 13 |
| 18 | 名古屋大学 | [361011078](https://www.openstreetmap.org/node/361011078) | 13 |
| 19 | 八事日赤 | [361011173](https://www.openstreetmap.org/node/361011173) | 12 |
| 20 | 八事 | [361011096](https://www.openstreetmap.org/node/361011096) | 5 |
| 21 | 総合リハビリセンター | [361011500](https://www.openstreetmap.org/node/361011500) | 12 |
| 22 | 瑞穂運動場東 | [361011251](https://www.openstreetmap.org/node/361011251) | 12 |
| 23 | 新瑞橋 | [9139714667](https://www.openstreetmap.org/node/9139714667) | 2 |
| 24 | 妙音通 | [361011224](https://www.openstreetmap.org/node/361011224) | 13 |
| 25 | 堀田 | [361011238](https://www.openstreetmap.org/node/361011238) | 14 |
| 26 | 熱田神宮伝馬町 | [361011495](https://www.openstreetmap.org/node/361011495) | 14 |
| 27 | 熱田神宮西 | [361011483](https://www.openstreetmap.org/node/361011483) | 15 |
| 28 | 西高蔵 | [361011220](https://www.openstreetmap.org/node/361011220) | 13 |
