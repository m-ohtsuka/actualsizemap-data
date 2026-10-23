# 山手線 線形データの出典

このファイルは `tools/build_yamanote.py build` が生成する。手で編集しない。

| 項目 | 内容 |
|---|---|
| データ版（dataVersion） | `yamanote-20261022-2` |
| 生成日（UTC） | 2026-10-23 |
| 出典 | OpenStreetMap relation [1972920](https://www.openstreetmap.org/relation/1972920)（JR山手線 (外回り)）版 130（relationの最終更新 2026-10-08T05:49:00Z） |
| 取得方法 | OSM API 0.6 `GET https://api.openstreetmap.org/api/0.6/relation/1972920/full.json` |
| 取得時刻（UTC） | 2026-10-22T13:56:33Z |
| 採用方向 | 外回り（片方向のみ。もう一方の方向・並行線・留置線は含めない） |
| 加工内容 | relationの経路メンバー（role ""）のwayを接続順に並べ、向きを揃えて1本の閉じた折れ線にした。隣接wayの共有端点の重複を除いた。簡略化・直線補完はしていない |
| 点数 | 904（先頭と末尾は同一点） |
| 全長（WGS84測地線） | 34.460 km |
| 隣接点の最大間隔 | 283.8 m |
| 基準点 | 緯度 35.6786781、経度 139.7395448（正距円筒型の局所平面に投影した外接矩形の中心） |
| 駅 | 30駅。relationの stop メンバー（停車位置のノード）を並び順に使い、重複（起点と終点）は1つにした。どの駅も線形の点列に含まれ、点列の中の順序が駅の並びと同じであることを確かめた |
| ライセンス | © OpenStreetMap contributors、[ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/)（個々の内容は [DbCL 1.0](https://opendatacommons.org/licenses/dbcl/1-0/)）。`../LICENSE.md` を参照 |

## 経路を構成するway（接続順）

| # | way ID | 版 |
|---|---|---|
| 1 | [781158785](https://www.openstreetmap.org/way/781158785) | 11 |
| 2 | [211240840](https://www.openstreetmap.org/way/211240840) | 25 |
| 3 | [1565076676](https://www.openstreetmap.org/way/1565076676) | 1 |
| 4 | [1565076675](https://www.openstreetmap.org/way/1565076675) | 2 |
| 5 | [1565541043](https://www.openstreetmap.org/way/1565541043) | 1 |
| 6 | [1565065372](https://www.openstreetmap.org/way/1565065372) | 1 |
| 7 | [115686505](https://www.openstreetmap.org/way/115686505) | 14 |
| 8 | [115686491](https://www.openstreetmap.org/way/115686491) | 17 |
| 9 | [211472304](https://www.openstreetmap.org/way/211472304) | 11 |
| 10 | [366845923](https://www.openstreetmap.org/way/366845923) | 18 |
| 11 | [1565065322](https://www.openstreetmap.org/way/1565065322) | 1 |
| 12 | [146060254](https://www.openstreetmap.org/way/146060254) | 34 |
| 13 | [835534703](https://www.openstreetmap.org/way/835534703) | 11 |
| 14 | [682735717](https://www.openstreetmap.org/way/682735717) | 16 |
| 15 | [146031134](https://www.openstreetmap.org/way/146031134) | 36 |
| 16 | [366845926](https://www.openstreetmap.org/way/366845926) | 18 |
| 17 | [1565065321](https://www.openstreetmap.org/way/1565065321) | 1 |
| 18 | [146031126](https://www.openstreetmap.org/way/146031126) | 33 |
| 19 | [74265106](https://www.openstreetmap.org/way/74265106) | 37 |
| 20 | [211954240](https://www.openstreetmap.org/way/211954240) | 31 |
| 21 | [211954204](https://www.openstreetmap.org/way/211954204) | 36 |
| 22 | [1091166131](https://www.openstreetmap.org/way/1091166131) | 9 |
| 23 | [211954311](https://www.openstreetmap.org/way/211954311) | 37 |
| 24 | [211954376](https://www.openstreetmap.org/way/211954376) | 31 |
| 25 | [211954476](https://www.openstreetmap.org/way/211954476) | 31 |
| 26 | [211954488](https://www.openstreetmap.org/way/211954488) | 33 |
| 27 | [664714514](https://www.openstreetmap.org/way/664714514) | 16 |
| 28 | [664714518](https://www.openstreetmap.org/way/664714518) | 14 |
| 29 | [211954409](https://www.openstreetmap.org/way/211954409) | 32 |
| 30 | [1565065362](https://www.openstreetmap.org/way/1565065362) | 1 |
| 31 | [211954330](https://www.openstreetmap.org/way/211954330) | 31 |
| 32 | [211954255](https://www.openstreetmap.org/way/211954255) | 32 |
| 33 | [211954382](https://www.openstreetmap.org/way/211954382) | 32 |
| 34 | [211954396](https://www.openstreetmap.org/way/211954396) | 31 |
| 35 | [74271106](https://www.openstreetmap.org/way/74271106) | 36 |
| 36 | [211954364](https://www.openstreetmap.org/way/211954364) | 34 |
| 37 | [962257133](https://www.openstreetmap.org/way/962257133) | 8 |
| 38 | [211954470](https://www.openstreetmap.org/way/211954470) | 33 |
| 39 | [211954211](https://www.openstreetmap.org/way/211954211) | 31 |
| 40 | [142253572](https://www.openstreetmap.org/way/142253572) | 36 |
| 41 | [142253570](https://www.openstreetmap.org/way/142253570) | 34 |
| 42 | [142253560](https://www.openstreetmap.org/way/142253560) | 38 |
| 43 | [142253567](https://www.openstreetmap.org/way/142253567) | 34 |
| 44 | [142253581](https://www.openstreetmap.org/way/142253581) | 37 |
| 45 | [1565065472](https://www.openstreetmap.org/way/1565065472) | 1 |
| 46 | [211954209](https://www.openstreetmap.org/way/211954209) | 35 |
| 47 | [853258594](https://www.openstreetmap.org/way/853258594) | 11 |
| 48 | [853258588](https://www.openstreetmap.org/way/853258588) | 12 |
| 49 | [211954421](https://www.openstreetmap.org/way/211954421) | 40 |
| 50 | [146060265](https://www.openstreetmap.org/way/146060265) | 37 |
| 51 | [146060273](https://www.openstreetmap.org/way/146060273) | 42 |
| 52 | [146060261](https://www.openstreetmap.org/way/146060261) | 35 |
| 53 | [146060266](https://www.openstreetmap.org/way/146060266) | 38 |
| 54 | [146060260](https://www.openstreetmap.org/way/146060260) | 34 |
| 55 | [155269655](https://www.openstreetmap.org/way/155269655) | 33 |
| 56 | [212294068](https://www.openstreetmap.org/way/212294068) | 38 |
| 57 | [212294073](https://www.openstreetmap.org/way/212294073) | 33 |
| 58 | [155269650](https://www.openstreetmap.org/way/155269650) | 34 |
| 59 | [144430737](https://www.openstreetmap.org/way/144430737) | 41 |
| 60 | [212294075](https://www.openstreetmap.org/way/212294075) | 35 |
| 61 | [212294071](https://www.openstreetmap.org/way/212294071) | 34 |
| 62 | [212294069](https://www.openstreetmap.org/way/212294069) | 34 |
| 63 | [212294059](https://www.openstreetmap.org/way/212294059) | 37 |
| 64 | [212294065](https://www.openstreetmap.org/way/212294065) | 36 |
| 65 | [230395545](https://www.openstreetmap.org/way/230395545) | 40 |
| 66 | [853254027](https://www.openstreetmap.org/way/853254027) | 12 |
| 67 | [853254028](https://www.openstreetmap.org/way/853254028) | 13 |
| 68 | [144430732](https://www.openstreetmap.org/way/144430732) | 43 |
| 69 | [144430733](https://www.openstreetmap.org/way/144430733) | 33 |
| 70 | [144477685](https://www.openstreetmap.org/way/144477685) | 37 |
| 71 | [144477672](https://www.openstreetmap.org/way/144477672) | 34 |
| 72 | [144430740](https://www.openstreetmap.org/way/144430740) | 37 |
| 73 | [155269651](https://www.openstreetmap.org/way/155269651) | 31 |
| 74 | [155269656](https://www.openstreetmap.org/way/155269656) | 32 |
| 75 | [155269642](https://www.openstreetmap.org/way/155269642) | 31 |
| 76 | [155269660](https://www.openstreetmap.org/way/155269660) | 34 |
| 77 | [155269640](https://www.openstreetmap.org/way/155269640) | 30 |
| 78 | [155269661](https://www.openstreetmap.org/way/155269661) | 37 |
| 79 | [753700497](https://www.openstreetmap.org/way/753700497) | 17 |
| 80 | [198609686](https://www.openstreetmap.org/way/198609686) | 32 |
| 81 | [198609688](https://www.openstreetmap.org/way/198609688) | 35 |
| 82 | [155269643](https://www.openstreetmap.org/way/155269643) | 30 |
| 83 | [155269636](https://www.openstreetmap.org/way/155269636) | 35 |
| 84 | [155269638](https://www.openstreetmap.org/way/155269638) | 31 |
| 85 | [155269658](https://www.openstreetmap.org/way/155269658) | 37 |
| 86 | [1414347376](https://www.openstreetmap.org/way/1414347376) | 2 |
| 87 | [1414347375](https://www.openstreetmap.org/way/1414347375) | 4 |
| 88 | [155308676](https://www.openstreetmap.org/way/155308676) | 31 |
| 89 | [155308660](https://www.openstreetmap.org/way/155308660) | 34 |
| 90 | [155308635](https://www.openstreetmap.org/way/155308635) | 32 |
| 91 | [155308689](https://www.openstreetmap.org/way/155308689) | 33 |
| 92 | [155308684](https://www.openstreetmap.org/way/155308684) | 32 |
| 93 | [155308672](https://www.openstreetmap.org/way/155308672) | 34 |
| 94 | [155308697](https://www.openstreetmap.org/way/155308697) | 32 |
| 95 | [155308624](https://www.openstreetmap.org/way/155308624) | 34 |
| 96 | [709822634](https://www.openstreetmap.org/way/709822634) | 16 |
| 97 | [709822632](https://www.openstreetmap.org/way/709822632) | 16 |
| 98 | [1565065309](https://www.openstreetmap.org/way/1565065309) | 1 |
| 99 | [1565065308](https://www.openstreetmap.org/way/1565065308) | 1 |
| 100 | [155308679](https://www.openstreetmap.org/way/155308679) | 32 |
| 101 | [155308708](https://www.openstreetmap.org/way/155308708) | 33 |
| 102 | [145788808](https://www.openstreetmap.org/way/145788808) | 33 |
| 103 | [145788849](https://www.openstreetmap.org/way/145788849) | 32 |
| 104 | [835755067](https://www.openstreetmap.org/way/835755067) | 12 |
| 105 | [835755066](https://www.openstreetmap.org/way/835755066) | 13 |
| 106 | [366845924](https://www.openstreetmap.org/way/366845924) | 22 |
| 107 | [1565072864](https://www.openstreetmap.org/way/1565072864) | 1 |
| 108 | [1565072863](https://www.openstreetmap.org/way/1565072863) | 1 |
| 109 | [1565072862](https://www.openstreetmap.org/way/1565072862) | 1 |
| 110 | [1565072861](https://www.openstreetmap.org/way/1565072861) | 1 |
| 111 | [1565072860](https://www.openstreetmap.org/way/1565072860) | 1 |
| 112 | [1565072859](https://www.openstreetmap.org/way/1565072859) | 1 |
| 113 | [184543315](https://www.openstreetmap.org/way/184543315) | 32 |
| 114 | [184543314](https://www.openstreetmap.org/way/184543314) | 33 |
| 115 | [184543313](https://www.openstreetmap.org/way/184543313) | 32 |
| 116 | [101530490](https://www.openstreetmap.org/way/101530490) | 44 |
| 117 | [1565073001](https://www.openstreetmap.org/way/1565073001) | 1 |
| 118 | [1565073000](https://www.openstreetmap.org/way/1565073000) | 1 |
| 119 | [1565072999](https://www.openstreetmap.org/way/1565072999) | 1 |
| 120 | [1565072848](https://www.openstreetmap.org/way/1565072848) | 1 |
| 121 | [1565072847](https://www.openstreetmap.org/way/1565072847) | 1 |
| 122 | [1565072846](https://www.openstreetmap.org/way/1565072846) | 2 |
| 123 | [144131733](https://www.openstreetmap.org/way/144131733) | 34 |
| 124 | [34282728](https://www.openstreetmap.org/way/34282728) | 55 |
| 125 | [1565541058](https://www.openstreetmap.org/way/1565541058) | 1 |
| 126 | [1565541057](https://www.openstreetmap.org/way/1565541057) | 1 |
| 127 | [1565073005](https://www.openstreetmap.org/way/1565073005) | 1 |
| 128 | [1565073004](https://www.openstreetmap.org/way/1565073004) | 1 |
| 129 | [1565073003](https://www.openstreetmap.org/way/1565073003) | 1 |
| 130 | [1565073002](https://www.openstreetmap.org/way/1565073002) | 1 |
| 131 | [144126069](https://www.openstreetmap.org/way/144126069) | 32 |
| 132 | [144126045](https://www.openstreetmap.org/way/144126045) | 42 |
| 133 | [183185952](https://www.openstreetmap.org/way/183185952) | 31 |
| 134 | [183185960](https://www.openstreetmap.org/way/183185960) | 33 |
| 135 | [183187946](https://www.openstreetmap.org/way/183187946) | 11 |
| 136 | [834998693](https://www.openstreetmap.org/way/834998693) | 8 |
| 137 | [834998692](https://www.openstreetmap.org/way/834998692) | 6 |
| 138 | [183187948](https://www.openstreetmap.org/way/183187948) | 34 |
| 139 | [897389518](https://www.openstreetmap.org/way/897389518) | 5 |
| 140 | [776865651](https://www.openstreetmap.org/way/776865651) | 9 |
| 141 | [776865648](https://www.openstreetmap.org/way/776865648) | 10 |
| 142 | [776866954](https://www.openstreetmap.org/way/776866954) | 9 |
| 143 | [853371783](https://www.openstreetmap.org/way/853371783) | 7 |
| 144 | [776865624](https://www.openstreetmap.org/way/776865624) | 9 |
| 145 | [776865615](https://www.openstreetmap.org/way/776865615) | 10 |
| 146 | [1566392264](https://www.openstreetmap.org/way/1566392264) | 1 |
| 147 | [211148541](https://www.openstreetmap.org/way/211148541) | 14 |
| 148 | [211148521](https://www.openstreetmap.org/way/211148521) | 11 |
| 149 | [211148531](https://www.openstreetmap.org/way/211148531) | 15 |
| 150 | [396521160](https://www.openstreetmap.org/way/396521160) | 9 |
| 151 | [396521167](https://www.openstreetmap.org/way/396521167) | 10 |
| 152 | [211148539](https://www.openstreetmap.org/way/211148539) | 13 |
| 153 | [396521163](https://www.openstreetmap.org/way/396521163) | 10 |
| 154 | [396521162](https://www.openstreetmap.org/way/396521162) | 10 |
| 155 | [211148577](https://www.openstreetmap.org/way/211148577) | 13 |
| 156 | [211148570](https://www.openstreetmap.org/way/211148570) | 11 |
| 157 | [211148615](https://www.openstreetmap.org/way/211148615) | 12 |
| 158 | [211148552](https://www.openstreetmap.org/way/211148552) | 11 |
| 159 | [211148576](https://www.openstreetmap.org/way/211148576) | 13 |
| 160 | [211148504](https://www.openstreetmap.org/way/211148504) | 12 |
| 161 | [211148604](https://www.openstreetmap.org/way/211148604) | 19 |
| 162 | [211148533](https://www.openstreetmap.org/way/211148533) | 12 |
| 163 | [211148568](https://www.openstreetmap.org/way/211148568) | 31 |
| 164 | [211148517](https://www.openstreetmap.org/way/211148517) | 11 |
| 165 | [897118569](https://www.openstreetmap.org/way/897118569) | 3 |
| 166 | [211148603](https://www.openstreetmap.org/way/211148603) | 16 |
| 167 | [897118564](https://www.openstreetmap.org/way/897118564) | 4 |
| 168 | [211148548](https://www.openstreetmap.org/way/211148548) | 11 |
| 169 | [211148553](https://www.openstreetmap.org/way/211148553) | 11 |
| 170 | [211148601](https://www.openstreetmap.org/way/211148601) | 11 |
| 171 | [211148584](https://www.openstreetmap.org/way/211148584) | 11 |
| 172 | [211148520](https://www.openstreetmap.org/way/211148520) | 11 |
| 173 | [211148606](https://www.openstreetmap.org/way/211148606) | 11 |
| 174 | [211148498](https://www.openstreetmap.org/way/211148498) | 11 |
| 175 | [211148532](https://www.openstreetmap.org/way/211148532) | 16 |
| 176 | [211148508](https://www.openstreetmap.org/way/211148508) | 12 |
| 177 | [1381338055](https://www.openstreetmap.org/way/1381338055) | 3 |
| 178 | [211148538](https://www.openstreetmap.org/way/211148538) | 46 |
| 179 | [203301416](https://www.openstreetmap.org/way/203301416) | 11 |
| 180 | [203301419](https://www.openstreetmap.org/way/203301419) | 15 |
| 181 | [203301415](https://www.openstreetmap.org/way/203301415) | 11 |
| 182 | [203301417](https://www.openstreetmap.org/way/203301417) | 20 |
| 183 | [203301418](https://www.openstreetmap.org/way/203301418) | 13 |
| 184 | [211240853](https://www.openstreetmap.org/way/211240853) | 11 |
| 185 | [211240826](https://www.openstreetmap.org/way/211240826) | 12 |
| 186 | [203301414](https://www.openstreetmap.org/way/203301414) | 13 |
| 187 | [203293540](https://www.openstreetmap.org/way/203293540) | 11 |
| 188 | [203293547](https://www.openstreetmap.org/way/203293547) | 13 |
| 189 | [203293542](https://www.openstreetmap.org/way/203293542) | 11 |
| 190 | [203293556](https://www.openstreetmap.org/way/203293556) | 14 |
| 191 | [203293541](https://www.openstreetmap.org/way/203293541) | 11 |
| 192 | [203293539](https://www.openstreetmap.org/way/203293539) | 14 |
| 193 | [203193832](https://www.openstreetmap.org/way/203193832) | 13 |
| 194 | [203293551](https://www.openstreetmap.org/way/203293551) | 19 |
| 195 | [203241887](https://www.openstreetmap.org/way/203241887) | 13 |
| 196 | [203241889](https://www.openstreetmap.org/way/203241889) | 15 |
| 197 | [211240812](https://www.openstreetmap.org/way/211240812) | 12 |
| 198 | [211240865](https://www.openstreetmap.org/way/211240865) | 12 |
| 199 | [211240863](https://www.openstreetmap.org/way/211240863) | 12 |
| 200 | [1384655043](https://www.openstreetmap.org/way/1384655043) | 3 |
| 201 | [1384655044](https://www.openstreetmap.org/way/1384655044) | 2 |
| 202 | [203193834](https://www.openstreetmap.org/way/203193834) | 17 |
| 203 | [211240831](https://www.openstreetmap.org/way/211240831) | 11 |
| 204 | [211240829](https://www.openstreetmap.org/way/211240829) | 12 |
| 205 | [1565131742](https://www.openstreetmap.org/way/1565131742) | 1 |
| 206 | [211240810](https://www.openstreetmap.org/way/211240810) | 10 |
| 207 | [211240871](https://www.openstreetmap.org/way/211240871) | 14 |
| 208 | [1565065371](https://www.openstreetmap.org/way/1565065371) | 1 |
| 209 | [1565065370](https://www.openstreetmap.org/way/1565065370) | 1 |
| 210 | [207112001](https://www.openstreetmap.org/way/207112001) | 10 |
| 211 | [207111994](https://www.openstreetmap.org/way/207111994) | 12 |
| 212 | [1565065381](https://www.openstreetmap.org/way/1565065381) | 1 |
| 213 | [1565065380](https://www.openstreetmap.org/way/1565065380) | 1 |
| 214 | [1565065379](https://www.openstreetmap.org/way/1565065379) | 1 |
| 215 | [1565065378](https://www.openstreetmap.org/way/1565065378) | 1 |
| 216 | [207111996](https://www.openstreetmap.org/way/207111996) | 10 |
| 217 | [1459542898](https://www.openstreetmap.org/way/1459542898) | 3 |
| 218 | [1459542899](https://www.openstreetmap.org/way/1459542899) | 2 |
| 219 | [207112003](https://www.openstreetmap.org/way/207112003) | 21 |
| 220 | [746257931](https://www.openstreetmap.org/way/746257931) | 6 |
| 221 | [695796250](https://www.openstreetmap.org/way/695796250) | 17 |
| 222 | [1527862949](https://www.openstreetmap.org/way/1527862949) | 1 |
| 223 | [854519240](https://www.openstreetmap.org/way/854519240) | 7 |

## 駅（並び順）

| # | 駅名 | node ID | 版 |
|---|---|---|---|
| 1 | 品川 | [3589537624](https://www.openstreetmap.org/node/3589537624) | 30 |
| 2 | 大崎 | [3708277009](https://www.openstreetmap.org/node/3708277009) | 28 |
| 3 | 五反田 | [1593325906](https://www.openstreetmap.org/node/1593325906) | 22 |
| 4 | 目黒 | [1593326191](https://www.openstreetmap.org/node/1593326191) | 2 |
| 5 | 恵比寿 | [2218777508](https://www.openstreetmap.org/node/2218777508) | 26 |
| 6 | 渋谷 | [1593485539](https://www.openstreetmap.org/node/1593485539) | 31 |
| 7 | 原宿 | [1579675415](https://www.openstreetmap.org/node/1579675415) | 24 |
| 8 | 代々木 | [1658981778](https://www.openstreetmap.org/node/1658981778) | 26 |
| 9 | 新宿 | [3558156201](https://www.openstreetmap.org/node/3558156201) | 10 |
| 10 | 新大久保 | [3708277017](https://www.openstreetmap.org/node/3708277017) | 26 |
| 11 | 高田馬場 | [3708279825](https://www.openstreetmap.org/node/3708279825) | 26 |
| 12 | 目白 | [3708276253](https://www.openstreetmap.org/node/3708276253) | 25 |
| 13 | 池袋 | [3558156196](https://www.openstreetmap.org/node/3558156196) | 28 |
| 14 | 大塚 | [1950369552](https://www.openstreetmap.org/node/1950369552) | 3 |
| 15 | 巣鴨 | [3708277019](https://www.openstreetmap.org/node/3708277019) | 24 |
| 16 | 駒込 | [3708276248](https://www.openstreetmap.org/node/3708276248) | 24 |
| 17 | 田端 | [3708277022](https://www.openstreetmap.org/node/3708277022) | 28 |
| 18 | 西日暮里 | [3708277002](https://www.openstreetmap.org/node/3708277002) | 25 |
| 19 | 日暮里 | [1591333868](https://www.openstreetmap.org/node/1591333868) | 27 |
| 20 | 鶯谷 | [3708279854](https://www.openstreetmap.org/node/3708279854) | 25 |
| 21 | 上野 | [3708279849](https://www.openstreetmap.org/node/3708279849) | 25 |
| 22 | 御徒町 | [1593268411](https://www.openstreetmap.org/node/1593268411) | 26 |
| 23 | 秋葉原 | [3708276971](https://www.openstreetmap.org/node/3708276971) | 29 |
| 24 | 神田 | [1593264885](https://www.openstreetmap.org/node/1593264885) | 28 |
| 25 | 東京 | [3589537652](https://www.openstreetmap.org/node/3589537652) | 29 |
| 26 | 有楽町 | [3708279864](https://www.openstreetmap.org/node/3708279864) | 27 |
| 27 | 新橋 | [393101195](https://www.openstreetmap.org/node/393101195) | 29 |
| 28 | 浜松町 | [393105021](https://www.openstreetmap.org/node/393105021) | 31 |
| 29 | 田町 | [3708279827](https://www.openstreetmap.org/node/3708279827) | 26 |
| 30 | 高輪ゲートウェイ | [7293401979](https://www.openstreetmap.org/node/7293401979) | 10 |
