# 鈴鹿サーキット 外形データの出典

このファイルは `tools/build_data.py build suzuka-circuit` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | 三重県鈴鹿市（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap way [775428456](https://www.openstreetmap.org/way/775428456)（鈴鹿サーキット）版 11（wayの最終更新 2025-12-27T00:35:26Z） |
| OSMのタグ | `area:highway=raceway`、`leisure=sports_centre`、`name=鈴鹿サーキット`、`name:en=Suzuka Circuit`、`sport=motor`、`wikidata=Q174170`、`wikipedia=ja:鈴鹿サーキット`、`wikipedia:en=Suzuka_Circuit` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/775428456/full.json` |
| 取得時刻（UTC） | 2026-11-14T22:59:44Z |
| 外形の範囲 | レースコースの区域（遊園地・ホテルは含まない） |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 216（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 7.453 km |
| 隣接点の最大間隔 | 140.5 m |
| 基準点 | 緯度 34.8437411、経度 136.5324037（正距円筒型の局所平面に投影した外接矩形の中心） |
| 細部 | 40本。輪郭の内側の形が分かるwayを、1本ずつ並び順のまま線にした。つなぎ合わせ・簡略化・直線補完はしていない。上の取得方法と同じく、wayごとに OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/<way ID>/full.json` で取得した（取得時刻は下の表）。細部のwayは、OpenStreetMap relation [284570](https://www.openstreetmap.org/relation/284570)（鈴鹿サーキット）版 12 の経路のメンバー（role ""）とちょうど一致することを確かめた |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 細部（並び順）

| 名前 | way ID | 版 | 形 | 点数 | 取得時刻（UTC） | OSMのタグ |
|---|---|---|---|---|---|---|
| 1コーナー | [183391643](https://www.openstreetmap.org/way/183391643) | 12 | 閉じていない線 | 13 | 2026-11-14T22:59:46Z | `highway=raceway`、`name=1コーナー`、`name:en=First Turn`、`name:es=Primer giro`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=1`、`sport=motor`、`surface=asphalt`、`width=14` |
| コース | [175231434](https://www.openstreetmap.org/way/175231434) | 8 | 閉じていない線 | 2 | 2026-11-14T22:59:46Z | `bridge=yes`、`highway=raceway`、`layer=1`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=13` |
| 130R | [183391652](https://www.openstreetmap.org/way/183391652) | 9 | 閉じていない線 | 16 | 2026-11-14T22:59:47Z | `highway=raceway`、`name=130R`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=15`、`sport=motor`、`surface=asphalt`、`width=13` |
| コース | [183391660](https://www.openstreetmap.org/way/183391660) | 10 | 閉じていない線 | 8 | 2026-11-14T22:59:48Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=13` |
| 日立オートモティブシステムズシケイン | [411289989](https://www.openstreetmap.org/way/411289989) | 7 | 閉じていない線 | 7 | 2026-11-14T22:59:48Z | `highway=raceway`、`name=日立オートモティブシステムズシケイン`、`name:en=Hitachi Automotive Systems Chicane`、`name:es=Chilcana Hitachi Automotive Systems`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=16`、`sport=motor`、`surface=asphalt`、`width=11` |
| 日立オートモティブシステムズシケイン | [183391637](https://www.openstreetmap.org/way/183391637) | 8 | 閉じていない線 | 2 | 2026-11-14T22:59:49Z | `highway=raceway`、`name=日立オートモティブシステムズシケイン`、`name:en=Hitachi Automotive Systems Chicane`、`name:es=Chilcana Hitachi Automotive Systems`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| 日立Astemoシケイン | [183391639](https://www.openstreetmap.org/way/183391639) | 8 | 閉じていない線 | 7 | 2026-11-14T22:59:50Z | `highway=raceway`、`name=日立Astemoシケイン`、`name:en=Hitachi Astemo Chicane`、`name:es=Chilcana Hitachi Automotive Systems`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=17`、`sport=motor`、`surface=asphalt`、`width=11` |
| 日立オートモティブシステムズシケイン | [183391638](https://www.openstreetmap.org/way/183391638) | 7 | 閉じていない線 | 2 | 2026-11-14T22:59:50Z | `highway=raceway`、`name=日立オートモティブシステムズシケイン`、`name:en=Hitachi Automotive Systems Chicane`、`name:es=Chilcana Hitachi Automotive Systems`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [183391640](https://www.openstreetmap.org/way/183391640) | 9 | 閉じていない線 | 7 | 2026-11-14T22:59:50Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=18`、`sport=motor`、`surface=asphalt`、`width=13` |
| コース | [183391661](https://www.openstreetmap.org/way/183391661) | 8 | 閉じていない線 | 7 | 2026-11-14T22:59:51Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=18`、`sport=motor`、`surface=asphalt`、`width=13` |
| メインストレート | [183391665](https://www.openstreetmap.org/way/183391665) | 9 | 閉じていない線 | 9 | 2026-11-14T22:59:52Z | `highway=raceway`、`name=メインストレート`、`name:en=Main straight`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=15` |
| コース | [183391645](https://www.openstreetmap.org/way/183391645) | 8 | 閉じていない線 | 2 | 2026-11-14T22:59:53Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=14` |
| 2コーナー | [183391644](https://www.openstreetmap.org/way/183391644) | 10 | 閉じていない線 | 13 | 2026-11-14T22:59:53Z | `highway=raceway`、`name=2コーナー`、`name:en=Second Turn`、`name:es=Segundo giro`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=2`、`sport=motor`、`surface=asphalt`、`width=14` |
| コース | [183391657](https://www.openstreetmap.org/way/183391657) | 10 | 閉じていない線 | 3 | 2026-11-14T22:59:54Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| S字 | [183391636](https://www.openstreetmap.org/way/183391636) | 9 | 閉じていない線 | 8 | 2026-11-14T22:59:55Z | `highway=raceway`、`name=S字`、`name:en='S' Curves`、`name:es=Curvas 'S'`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=3`、`sport=motor`、`surface=asphalt`、`width=11` |
| デグナー1 | [183391641](https://www.openstreetmap.org/way/183391641) | 11 | 閉じていない線 | 4 | 2026-11-14T22:59:55Z | `highway=raceway`、`name=デグナー1`、`name:en=Degner Curve 1`、`name:es=Curva Degner 1`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=8`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [411295349](https://www.openstreetmap.org/way/411295349) | 7 | 閉じていない線 | 8 | 2026-11-14T22:59:55Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| NIPPO コーナー | [183391642](https://www.openstreetmap.org/way/183391642) | 14 | 閉じていない線 | 16 | 2026-11-14T22:59:56Z | `highway=raceway`、`name=NIPPO コーナー`、`name:en=NIPPO Corner`、`name:es=NIPPO Corner`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| NIPPO コーナー | [183391630](https://www.openstreetmap.org/way/183391630) | 11 | 閉じていない線 | 11 | 2026-11-14T22:59:56Z | `highway=raceway`、`layer=1`、`name=NIPPO コーナー`、`name:en=NIPPO Corner`、`name:es=NIPPO Corner`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=7`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [183391632](https://www.openstreetmap.org/way/183391632) | 9 | 閉じていない線 | 3 | 2026-11-14T22:59:57Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| 逆バンク | [183391631](https://www.openstreetmap.org/way/183391631) | 10 | 閉じていない線 | 14 | 2026-11-14T22:59:57Z | `highway=raceway`、`name=逆バンク`、`name:en=Gyaku Curve`、`name:es=Curva Gyaku`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=6`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [183391633](https://www.openstreetmap.org/way/183391633) | 8 | 閉じていない線 | 2 | 2026-11-14T22:59:58Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| S字 | [183391629](https://www.openstreetmap.org/way/183391629) | 10 | 閉じていない線 | 12 | 2026-11-14T22:59:59Z | `highway=raceway`、`name=S字`、`name:en='S' Curves`、`name:es=Curvas 'S'`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=5`、`sport=motor`、`surface=asphalt`、`width=11` |
| S字 | [183391634](https://www.openstreetmap.org/way/183391634) | 9 | 閉じていない線 | 2 | 2026-11-14T22:59:59Z | `highway=raceway`、`name=S字`、`name:en='S' Curves`、`name:es=Curvas 'S'`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| S字 | [183391628](https://www.openstreetmap.org/way/183391628) | 9 | 閉じていない線 | 11 | 2026-11-14T23:00:00Z | `highway=raceway`、`name=S字`、`name:en='S' Curves`、`name:es=Curvas 'S'`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=4`、`sport=motor`、`surface=asphalt`、`width=11` |
| S字 | [183391635](https://www.openstreetmap.org/way/183391635) | 10 | 閉じていない線 | 2 | 2026-11-14T23:00:01Z | `highway=raceway`、`name=S字`、`name:en='S' Curves`、`name:es=Curvas 'S'`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| 西ストレート | [411295348](https://www.openstreetmap.org/way/411295348) | 9 | 閉じていない線 | 19 | 2026-11-14T23:00:02Z | `highway=raceway`、`name=西ストレート`、`name:en=West straight`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=14` |
| スプーンカーブ | [183391648](https://www.openstreetmap.org/way/183391648) | 9 | 閉じていない線 | 15 | 2026-11-14T23:00:02Z | `highway=raceway`、`name=スプーンカーブ`、`name:en=Spoon Curve`、`name:es=Curva Spoon`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=14`、`sport=motor`、`surface=asphalt`、`width=14` |
| スプーンカーブ | [411295351](https://www.openstreetmap.org/way/411295351) | 8 | 閉じていない線 | 4 | 2026-11-14T23:00:03Z | `highway=raceway`、`name=スプーンカーブ`、`name:en=Spoon Curve`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=14` |
| スプーンカーブ | [183391647](https://www.openstreetmap.org/way/183391647) | 8 | 閉じていない線 | 11 | 2026-11-14T23:00:04Z | `highway=raceway`、`name=スプーンカーブ`、`name:en=Spoon Curve`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=13`、`sport=motor`、`surface=asphalt`、`width=14` |
| コース | [183391649](https://www.openstreetmap.org/way/183391649) | 8 | 閉じていない線 | 2 | 2026-11-14T23:00:04Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=14` |
| コース | [411295347](https://www.openstreetmap.org/way/411295347) | 7 | 閉じていない線 | 17 | 2026-11-14T23:00:04Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=12` |
| コース | [183391651](https://www.openstreetmap.org/way/183391651) | 8 | 閉じていない線 | 12 | 2026-11-14T23:00:05Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=12`、`sport=motor`、`surface=asphalt`、`width=12` |
| コース | [183391659](https://www.openstreetmap.org/way/183391659) | 8 | 閉じていない線 | 5 | 2026-11-14T23:00:06Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=12` |
| NISSINブレーキヘアピン | [183391646](https://www.openstreetmap.org/way/183391646) | 10 | 閉じていない線 | 11 | 2026-11-14T23:00:07Z | `highway=raceway`、`name=NISSINブレーキヘアピン`、`name:en=NISSIN Brake Hairpin`、`name:es=NISSIN Brake Hairpin`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=11`、`sport=motor`、`surface=asphalt`、`width=13` |
| コース | [183391658](https://www.openstreetmap.org/way/183391658) | 7 | 閉じていない線 | 2 | 2026-11-14T23:00:07Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [183391662](https://www.openstreetmap.org/way/183391662) | 7 | 閉じていない線 | 7 | 2026-11-14T23:00:08Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=10`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [183391655](https://www.openstreetmap.org/way/183391655) | 8 | 閉じていない線 | 2 | 2026-11-14T23:00:09Z | `covered=yes`、`highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
| デグナー2 | [183391664](https://www.openstreetmap.org/way/183391664) | 10 | 閉じていない線 | 8 | 2026-11-14T23:00:10Z | `highway=raceway`、`name=デグナー2`、`name:en=Degner Curve 2`、`name:es=Curva Degner 2`、`oneway=yes`、`oneway:bicycle=no`、`raceway:corner_number=9`、`sport=motor`、`surface=asphalt`、`width=11` |
| コース | [183391656](https://www.openstreetmap.org/way/183391656) | 7 | 閉じていない線 | 2 | 2026-11-14T23:00:10Z | `highway=raceway`、`oneway=yes`、`oneway:bicycle=no`、`sport=motor`、`surface=asphalt`、`width=11` |
