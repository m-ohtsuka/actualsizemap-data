# 福岡高速環状線 線形データの出典

このファイルは `tools/build_data.py build fukuoka-expressway-loop` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | 福岡県福岡市（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap relation [8022363](https://www.openstreetmap.org/relation/8022363)（福岡都市高速環状線内回り）版 30（relationの最終更新 2025-08-26T10:03:36Z） |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/relation/8022363/full.json` |
| 取得時刻（UTC） | 2026-11-14T12:14:13Z |
| 採用方向 | 内回り（片方向のみ。もう一方の方向・並行線・留置線は含めない） |
| 加工内容 | relationの経路メンバー（role ""）のwayを接続順に並べ、向きを揃えて1本の閉じた折れ線にした。隣接wayの共有端点の重複を除いた。簡略化・直線補完はしていない。どのwayも一方通行で、wayの向きが一周の向きと一致することを確かめた（ADR-037） |
| 点数 | 758（先頭と末尾は同一点） |
| 全長（WGS84測地線） | 34.666 km（relationに distance タグが無いため、全長は照合していない） |
| 隣接点の最大間隔 | 768.2 m |
| 基準点 | 緯度 33.5732505、経度 130.3888234（正距円筒型の局所平面に投影した外接矩形の中心） |
| 出口・JCT | 12か所。線の点のうち highway=motorway_junction のノード（採用方向で流出する出口と、分岐するJCT）を、線の並び順に使った。どれも線形の点列に1つだけ含まれることを確かめた（ADR-037） |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 経路を構成するway（接続順）

| # | way ID | 版 |
|---|---|---|
| 1 | [187013940](https://www.openstreetmap.org/way/187013940) | 11 |
| 2 | [63521214](https://www.openstreetmap.org/way/63521214) | 13 |
| 3 | [187713980](https://www.openstreetmap.org/way/187713980) | 10 |
| 4 | [187013914](https://www.openstreetmap.org/way/187013914) | 12 |
| 5 | [187013929](https://www.openstreetmap.org/way/187013929) | 8 |
| 6 | [172111447](https://www.openstreetmap.org/way/172111447) | 7 |
| 7 | [187013936](https://www.openstreetmap.org/way/187013936) | 14 |
| 8 | [187013930](https://www.openstreetmap.org/way/187013930) | 15 |
| 9 | [760732915](https://www.openstreetmap.org/way/760732915) | 4 |
| 10 | [726186024](https://www.openstreetmap.org/way/726186024) | 6 |
| 11 | [186981819](https://www.openstreetmap.org/way/186981819) | 15 |
| 12 | [742860952](https://www.openstreetmap.org/way/742860952) | 4 |
| 13 | [196866583](https://www.openstreetmap.org/way/196866583) | 18 |
| 14 | [186981838](https://www.openstreetmap.org/way/186981838) | 19 |
| 15 | [1317568122](https://www.openstreetmap.org/way/1317568122) | 2 |
| 16 | [742872212](https://www.openstreetmap.org/way/742872212) | 8 |
| 17 | [788091303](https://www.openstreetmap.org/way/788091303) | 6 |
| 18 | [725761171](https://www.openstreetmap.org/way/725761171) | 3 |
| 19 | [725761172](https://www.openstreetmap.org/way/725761172) | 4 |
| 20 | [725761173](https://www.openstreetmap.org/way/725761173) | 6 |
| 21 | [186981829](https://www.openstreetmap.org/way/186981829) | 16 |
| 22 | [186981830](https://www.openstreetmap.org/way/186981830) | 18 |
| 23 | [298780487](https://www.openstreetmap.org/way/298780487) | 7 |
| 24 | [62135356](https://www.openstreetmap.org/way/62135356) | 18 |
| 25 | [725768608](https://www.openstreetmap.org/way/725768608) | 9 |
| 26 | [744638626](https://www.openstreetmap.org/way/744638626) | 9 |
| 27 | [744324320](https://www.openstreetmap.org/way/744324320) | 9 |
| 28 | [744326433](https://www.openstreetmap.org/way/744326433) | 6 |
| 29 | [266078775](https://www.openstreetmap.org/way/266078775) | 14 |
| 30 | [180105221](https://www.openstreetmap.org/way/180105221) | 10 |
| 31 | [744324323](https://www.openstreetmap.org/way/744324323) | 3 |
| 32 | [180105213](https://www.openstreetmap.org/way/180105213) | 12 |
| 33 | [744109209](https://www.openstreetmap.org/way/744109209) | 5 |
| 34 | [258870492](https://www.openstreetmap.org/way/258870492) | 10 |
| 35 | [63519980](https://www.openstreetmap.org/way/63519980) | 14 |
| 36 | [63520003](https://www.openstreetmap.org/way/63520003) | 14 |
| 37 | [258870490](https://www.openstreetmap.org/way/258870490) | 9 |
| 38 | [180105220](https://www.openstreetmap.org/way/180105220) | 12 |
| 39 | [180105216](https://www.openstreetmap.org/way/180105216) | 10 |
| 40 | [180105218](https://www.openstreetmap.org/way/180105218) | 12 |
| 41 | [180105212](https://www.openstreetmap.org/way/180105212) | 18 |
| 42 | [840816742](https://www.openstreetmap.org/way/840816742) | 2 |
| 43 | [196990118](https://www.openstreetmap.org/way/196990118) | 11 |
| 44 | [63519928](https://www.openstreetmap.org/way/63519928) | 12 |
| 45 | [63520017](https://www.openstreetmap.org/way/63520017) | 10 |
| 46 | [63519941](https://www.openstreetmap.org/way/63519941) | 10 |
| 47 | [63519885](https://www.openstreetmap.org/way/63519885) | 10 |
| 48 | [63519900](https://www.openstreetmap.org/way/63519900) | 10 |
| 49 | [759870428](https://www.openstreetmap.org/way/759870428) | 4 |
| 50 | [434712326](https://www.openstreetmap.org/way/434712326) | 17 |
| 51 | [187013913](https://www.openstreetmap.org/way/187013913) | 11 |

## 出口・JCT（並び順）

| # | 名前 | node ID | 版 |
|---|---|---|---|
| 1 | 野芥出口 | [1864283722](https://www.openstreetmap.org/node/1864283722) | 7 |
| 2 | 堤出口 | [786533993](https://www.openstreetmap.org/node/786533993) | 8 |
| 3 | 野多目出口 | [786534151](https://www.openstreetmap.org/node/786534151) | 9 |
| 4 | 月隈JCT | [786506697](https://www.openstreetmap.org/node/786506697) | 18 |
| 5 | 半道橋出口 | [777811155](https://www.openstreetmap.org/node/777811155) | 10 |
| 6 | 千代出口 | [1855656066](https://www.openstreetmap.org/node/1855656066) | 10 |
| 7 | 千鳥橋JCT | [775274429](https://www.openstreetmap.org/node/775274429) | 9 |
| 8 | 築港出口 | [799100726](https://www.openstreetmap.org/node/799100726) | 9 |
| 9 | 天神北出口 | [1864202018](https://www.openstreetmap.org/node/1864202018) | 8 |
| 10 | 西公園出口 | [786506635](https://www.openstreetmap.org/node/786506635) | 9 |
| 11 | 姪浜出口 | [786506444](https://www.openstreetmap.org/node/786506444) | 9 |
| 12 | 福重出口 | [792973625](https://www.openstreetmap.org/node/792973625) | 9 |
