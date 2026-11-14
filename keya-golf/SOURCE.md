# 芥屋ゴルフ倶楽部 外形データの出典

このファイルは `tools/build_data.py build keya-golf` が生成する。手で編集しない。データ一式の版は `../catalog.json` の `dataVersion`。

| 項目 | 内容 |
|---|---|
| 生成日（UTC） | 2026-11-14 |
| 場所の説明 | 福岡県糸島市（メニューに出す。ADR-023） |
| 出典 | OpenStreetMap way [205599606](https://www.openstreetmap.org/way/205599606)（芥屋ゴルフ倶楽部 (Keya Golf Club)）版 5（wayの最終更新 2019-07-30T00:28:26Z） |
| OSMのタグ | `leisure=golf_course`、`name=芥屋ゴルフ倶楽部 (Keya Golf Club)`、`source=bing` |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/way/205599606/full.json` |
| 取得時刻（UTC） | 2026-11-14T02:25:56Z |
| 外形の範囲 | コースの境界 |
| 加工内容 | 閉じたway 1本のノードを、並び順のまま1本の閉じた折れ線にした。ほかのwayとのつなぎ合わせ・簡略化・直線補完はしていない |
| 点数 | 58（先頭と末尾は同一点） |
| 周長（WGS84測地線） | 4.795 km |
| 隣接点の最大間隔 | 275.9 m |
| 基準点 | 緯度 33.5857156、経度 130.1344333（正距円筒型の局所平面に投影した外接矩形の中心） |
| 細部 | なし |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |
