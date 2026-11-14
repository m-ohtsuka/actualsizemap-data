# 大阪環状線 線形データの出典

このファイルは `tools/build_data.py build osaka-loop` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | 大阪府大阪市（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap relation [10073683](https://www.openstreetmap.org/relation/10073683)（JR大阪環状線 (内回り)）版 48（relationの最終更新 2026-05-17T05:51:50Z） |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/relation/10073683/full.json` |
| 取得時刻（UTC） | 2026-11-14T14:25:45Z |
| 採用方向 | 内回り（片方向のみ。もう一方の方向・並行線・留置線は含めない） |
| 加工内容 | relationの経路メンバー（role ""）のwayを接続順に並べ、向きを揃えて1本の閉じた折れ線にした。隣接wayの共有端点の重複を除いた。簡略化・直線補完はしていない |
| 点数 | 600（先頭と末尾は同一点） |
| 全長（WGS84測地線） | 21.726 km（relationに distance タグが無いため、全長は照合していない） |
| 隣接点の最大間隔 | 312.6 m |
| 基準点 | 緯度 34.6762182、経度 135.4979444（正距円筒型の局所平面に投影した外接矩形の中心） |
| 駅 | 19駅。relationの stop メンバー（停車位置のノード）を並び順に使い、重複（起点と終点）は1つにした。どの駅も線形の点列に含まれ、点列の中の順序が駅の並びと同じであることを確かめた |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 経路を構成するway（接続順）

| # | way ID | 版 |
|---|---|---|
| 1 | [1373008687](https://www.openstreetmap.org/way/1373008687) | 2 |
| 2 | [642911814](https://www.openstreetmap.org/way/642911814) | 7 |
| 3 | [1355281629](https://www.openstreetmap.org/way/1355281629) | 2 |
| 4 | [152067265](https://www.openstreetmap.org/way/152067265) | 14 |
| 5 | [1073442162](https://www.openstreetmap.org/way/1073442162) | 3 |
| 6 | [1073442167](https://www.openstreetmap.org/way/1073442167) | 3 |
| 7 | [1073442166](https://www.openstreetmap.org/way/1073442166) | 4 |
| 8 | [1073442163](https://www.openstreetmap.org/way/1073442163) | 3 |
| 9 | [1073442168](https://www.openstreetmap.org/way/1073442168) | 4 |
| 10 | [1073442169](https://www.openstreetmap.org/way/1073442169) | 3 |
| 11 | [891061302](https://www.openstreetmap.org/way/891061302) | 5 |
| 12 | [891061300](https://www.openstreetmap.org/way/891061300) | 3 |
| 13 | [132628014](https://www.openstreetmap.org/way/132628014) | 16 |
| 14 | [891061295](https://www.openstreetmap.org/way/891061295) | 3 |
| 15 | [891061290](https://www.openstreetmap.org/way/891061290) | 5 |
| 16 | [1447873487](https://www.openstreetmap.org/way/1447873487) | 2 |
| 17 | [1447873485](https://www.openstreetmap.org/way/1447873485) | 2 |
| 18 | [91831289](https://www.openstreetmap.org/way/91831289) | 19 |
| 19 | [891061308](https://www.openstreetmap.org/way/891061308) | 3 |
| 20 | [891061307](https://www.openstreetmap.org/way/891061307) | 4 |
| 21 | [891061304](https://www.openstreetmap.org/way/891061304) | 3 |
| 22 | [891061311](https://www.openstreetmap.org/way/891061311) | 5 |
| 23 | [398762983](https://www.openstreetmap.org/way/398762983) | 14 |
| 24 | [891061312](https://www.openstreetmap.org/way/891061312) | 5 |
| 25 | [935433930](https://www.openstreetmap.org/way/935433930) | 5 |
| 26 | [396413926](https://www.openstreetmap.org/way/396413926) | 12 |
| 27 | [396413925](https://www.openstreetmap.org/way/396413925) | 9 |
| 28 | [396413922](https://www.openstreetmap.org/way/396413922) | 10 |
| 29 | [396413923](https://www.openstreetmap.org/way/396413923) | 9 |
| 30 | [608266429](https://www.openstreetmap.org/way/608266429) | 7 |
| 31 | [91831285](https://www.openstreetmap.org/way/91831285) | 21 |
| 32 | [1355281628](https://www.openstreetmap.org/way/1355281628) | 2 |
| 33 | [397144869](https://www.openstreetmap.org/way/397144869) | 9 |
| 34 | [397144884](https://www.openstreetmap.org/way/397144884) | 8 |
| 35 | [397144885](https://www.openstreetmap.org/way/397144885) | 9 |
| 36 | [397144880](https://www.openstreetmap.org/way/397144880) | 9 |
| 37 | [397144879](https://www.openstreetmap.org/way/397144879) | 11 |
| 38 | [397144871](https://www.openstreetmap.org/way/397144871) | 8 |
| 39 | [635678748](https://www.openstreetmap.org/way/635678748) | 7 |
| 40 | [635678746](https://www.openstreetmap.org/way/635678746) | 7 |
| 41 | [635678747](https://www.openstreetmap.org/way/635678747) | 8 |
| 42 | [397144892](https://www.openstreetmap.org/way/397144892) | 10 |
| 43 | [397144894](https://www.openstreetmap.org/way/397144894) | 10 |
| 44 | [397144895](https://www.openstreetmap.org/way/397144895) | 9 |
| 45 | [397144898](https://www.openstreetmap.org/way/397144898) | 10 |
| 46 | [397144900](https://www.openstreetmap.org/way/397144900) | 8 |
| 47 | [397144910](https://www.openstreetmap.org/way/397144910) | 10 |
| 48 | [397144916](https://www.openstreetmap.org/way/397144916) | 10 |
| 49 | [397144919](https://www.openstreetmap.org/way/397144919) | 11 |
| 50 | [397144921](https://www.openstreetmap.org/way/397144921) | 8 |
| 51 | [397144923](https://www.openstreetmap.org/way/397144923) | 11 |
| 52 | [1365461779](https://www.openstreetmap.org/way/1365461779) | 2 |
| 53 | [397144925](https://www.openstreetmap.org/way/397144925) | 11 |
| 54 | [397144928](https://www.openstreetmap.org/way/397144928) | 13 |
| 55 | [397144934](https://www.openstreetmap.org/way/397144934) | 12 |
| 56 | [610920134](https://www.openstreetmap.org/way/610920134) | 8 |
| 57 | [397145532](https://www.openstreetmap.org/way/397145532) | 10 |
| 58 | [397145531](https://www.openstreetmap.org/way/397145531) | 10 |
| 59 | [1395527473](https://www.openstreetmap.org/way/1395527473) | 2 |
| 60 | [1395527472](https://www.openstreetmap.org/way/1395527472) | 2 |
| 61 | [397145535](https://www.openstreetmap.org/way/397145535) | 12 |
| 62 | [1317039312](https://www.openstreetmap.org/way/1317039312) | 6 |
| 63 | [91831267](https://www.openstreetmap.org/way/91831267) | 27 |
| 64 | [91831268](https://www.openstreetmap.org/way/91831268) | 21 |
| 65 | [132325087](https://www.openstreetmap.org/way/132325087) | 20 |
| 66 | [1459301687](https://www.openstreetmap.org/way/1459301687) | 2 |
| 67 | [449230405](https://www.openstreetmap.org/way/449230405) | 7 |
| 68 | [449230402](https://www.openstreetmap.org/way/449230402) | 10 |
| 69 | [852469100](https://www.openstreetmap.org/way/852469100) | 4 |
| 70 | [852546498](https://www.openstreetmap.org/way/852546498) | 3 |
| 71 | [129317026](https://www.openstreetmap.org/way/129317026) | 19 |
| 72 | [1515105416](https://www.openstreetmap.org/way/1515105416) | 1 |
| 73 | [1515105424](https://www.openstreetmap.org/way/1515105424) | 1 |
| 74 | [1515105423](https://www.openstreetmap.org/way/1515105423) | 1 |
| 75 | [1515105422](https://www.openstreetmap.org/way/1515105422) | 1 |
| 76 | [1515105420](https://www.openstreetmap.org/way/1515105420) | 1 |
| 77 | [1515105419](https://www.openstreetmap.org/way/1515105419) | 1 |
| 78 | [1515105417](https://www.openstreetmap.org/way/1515105417) | 1 |
| 79 | [1515105418](https://www.openstreetmap.org/way/1515105418) | 1 |
| 80 | [122805877](https://www.openstreetmap.org/way/122805877) | 17 |
| 81 | [395280355](https://www.openstreetmap.org/way/395280355) | 13 |
| 82 | [1459296552](https://www.openstreetmap.org/way/1459296552) | 2 |
| 83 | [1515104403](https://www.openstreetmap.org/way/1515104403) | 1 |
| 84 | [1459296549](https://www.openstreetmap.org/way/1459296549) | 1 |
| 85 | [91831286](https://www.openstreetmap.org/way/91831286) | 26 |
| 86 | [395280364](https://www.openstreetmap.org/way/395280364) | 10 |
| 87 | [395280389](https://www.openstreetmap.org/way/395280389) | 12 |
| 88 | [139439184](https://www.openstreetmap.org/way/139439184) | 22 |
| 89 | [890926297](https://www.openstreetmap.org/way/890926297) | 4 |
| 90 | [890926302](https://www.openstreetmap.org/way/890926302) | 4 |
| 91 | [639976814](https://www.openstreetmap.org/way/639976814) | 7 |
| 92 | [527064010](https://www.openstreetmap.org/way/527064010) | 10 |
| 93 | [152067309](https://www.openstreetmap.org/way/152067309) | 13 |
| 94 | [842117642](https://www.openstreetmap.org/way/842117642) | 4 |

## 駅（並び順）

| # | 駅名 | node ID | 版 |
|---|---|---|---|
| 1 | 天王寺 | [6821295871](https://www.openstreetmap.org/node/6821295871) | 5 |
| 2 | 寺田町 | [346685339](https://www.openstreetmap.org/node/346685339) | 11 |
| 3 | 桃谷 | [346685351](https://www.openstreetmap.org/node/346685351) | 12 |
| 4 | 鶴橋 | [6821275921](https://www.openstreetmap.org/node/6821275921) | 4 |
| 5 | 玉造 | [6821267367](https://www.openstreetmap.org/node/6821267367) | 4 |
| 6 | 森ノ宮 | [6821220142](https://www.openstreetmap.org/node/6821220142) | 6 |
| 7 | 大阪城公園 | [6821211680](https://www.openstreetmap.org/node/6821211680) | 4 |
| 8 | 京橋 | [346685274](https://www.openstreetmap.org/node/346685274) | 20 |
| 9 | 桜ノ宮 | [6820905981](https://www.openstreetmap.org/node/6820905981) | 5 |
| 10 | 天満 | [6820861577](https://www.openstreetmap.org/node/6820861577) | 4 |
| 11 | 大阪 | [3203302167](https://www.openstreetmap.org/node/3203302167) | 9 |
| 12 | 福島 | [6336018203](https://www.openstreetmap.org/node/6336018203) | 4 |
| 13 | 野田 | [6818457281](https://www.openstreetmap.org/node/6818457281) | 4 |
| 14 | 西九条 | [6138650161](https://www.openstreetmap.org/node/6138650161) | 5 |
| 15 | 弁天町 | [346685234](https://www.openstreetmap.org/node/346685234) | 12 |
| 16 | 大正 | [346685371](https://www.openstreetmap.org/node/346685371) | 14 |
| 17 | 芦原橋 | [1453619780](https://www.openstreetmap.org/node/1453619780) | 6 |
| 18 | 今宮 | [258496073](https://www.openstreetmap.org/node/258496073) | 12 |
| 19 | 新今宮 | [6821344398](https://www.openstreetmap.org/node/6821344398) | 3 |
