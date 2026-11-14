# LHC 線形データの出典

このファイルは `tools/build_data.py build lhc` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | スイス・フランス ジュネーブ近郊（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap relation [9512017](https://www.openstreetmap.org/relation/9512017)（大型ハドロン衝突型加速器）版 12（relationの最終更新 2026-07-04T13:57:31Z） |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/relation/9512017/full.json` |
| 取得時刻（UTC） | 2026-11-14T22:39:06Z |
| 採用方向 | なし（方向の無い環。relationのwayを1周分。ADR-042） |
| 加工内容 | relationの経路メンバー（role ""）のwayを接続順に並べ、向きを揃えて1本の閉じた折れ線にした。隣接wayの共有端点の重複を除いた。簡略化・直線補完はしていない |
| 点数 | 276（先頭と末尾は同一点） |
| 全長（WGS84測地線） | 26.614 km（relationに distance タグが無いため、全長は照合していない） |
| 隣接点の最大間隔 | 527.7 m |
| 基準点 | 緯度 46.2727745、経度 6.0659176（正距円筒型の局所平面に投影した外接矩形の中心） |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 経路を構成するway（接続順）

| # | way ID | 版 |
|---|---|---|
| 1 | [685422600](https://www.openstreetmap.org/way/685422600) | 4 |
| 2 | [685422599](https://www.openstreetmap.org/way/685422599) | 7 |
| 3 | [685422602](https://www.openstreetmap.org/way/685422602) | 4 |
| 4 | [685422601](https://www.openstreetmap.org/way/685422601) | 4 |
| 5 | [685422609](https://www.openstreetmap.org/way/685422609) | 4 |
| 6 | [685422604](https://www.openstreetmap.org/way/685422604) | 4 |
| 7 | [685422603](https://www.openstreetmap.org/way/685422603) | 4 |
| 8 | [685422593](https://www.openstreetmap.org/way/685422593) | 7 |
| 9 | [685422592](https://www.openstreetmap.org/way/685422592) | 4 |
| 10 | [310046324](https://www.openstreetmap.org/way/310046324) | 14 |
| 11 | [685422595](https://www.openstreetmap.org/way/685422595) | 4 |
| 12 | [685422594](https://www.openstreetmap.org/way/685422594) | 4 |
| 13 | [685422591](https://www.openstreetmap.org/way/685422591) | 4 |
| 14 | [685422596](https://www.openstreetmap.org/way/685422596) | 5 |
| 15 | [685422598](https://www.openstreetmap.org/way/685422598) | 4 |
| 16 | [685422597](https://www.openstreetmap.org/way/685422597) | 4 |
