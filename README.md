# 氷川重奏 HIKAWA ENSEMBLE ── mitsulab

氷川参道（さいたま市大宮区）のまわりを、地図・3D の建物・樹木・生きものの記録・歴史・文化の層で重ねて見る、ブラウザで動く資料地図です。

公開先：<https://mitsulab-soil.github.io/HIKAWA-ENSEMBLE/>

このリポジトリの `index.html` は、mitsulab の作業場にある元（`atlas-v5.html`）から書き出したものです。ここを直接直さず、元を直して書き出し直します。

## 出典とライセンス

| もの | 出どころ | 条件 |
|---|---|---|
| 地図・写真のタイル、標高 | [国土地理院](https://maps.gsi.go.jp/development/ichiran.html) | [国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)（公共データ利用規約 第1.0版＝PDL1.0 に準拠） |
| 3D の建物 | [3D都市モデル（Project PLATEAU）さいたま市（2025年度）](https://www.geospatial.jp/ckan/dataset/plateau-11100-saitama-shi-2025)（国土交通省） | 公共データ利用規約 第1.0版（PDL1.0）。加工して作成 |
| 参道の線・境内・駅・鳥居・街の木などの位置 | © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright) | [ODbL](https://opendatacommons.org/licenses/odbl/) |
| 学名 | [GBIF](https://www.gbif.org/) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 生きものの観察記録 | [iNaturalist](https://www.inaturalist.org/) の投稿者のみなさん（ページを開くたびに API から受け取る） | 記録（種名・日付・座標・精度）を地図に立てる。位置をぼかされた記録は地図に出さない |
| 生きものの写真 | iNaturalist の投稿者のみなさん（iNaturalist の配信から直接表示。このリポジトリには入っていない） | **CC0・CC BY・CC BY-SA の写真だけを出す。**写真の下に作者・ライセンス名（本文へのリンク）・iNaturalist の写真の頁を出す。CC BY-NC・CC BY-ND などの写真と全権留保の写真は出さず、「この一枚は許可の外」と書いて iNaturalist の記録へのリンクだけを置く |
| 地球儀と 3D の描画 | [CesiumJS](https://cesium.com/platform/cesiumjs/)（jsDelivr から読み込み） | [Apache-2.0](https://github.com/CesiumGS/cesium/blob/main/LICENSE.md) |
| 書体 | [Google Fonts](https://fonts.google.com/)（Shippori Mincho・JetBrains Mono） | SIL Open Font License 1.1 |

樹木の配置は『氷川参道の樹木調査』（さいたま市）の本数・樹種構成・区間別集計にもとづく概略配置で、一本ずつの実測位置ではありません。歴史・文化の各項目の出典は、ページの中のカードと「受信経路の一覧（出典）」に書いています。

## 現在地について

ブラウザの位置情報を使うときも、座標をこの端末の外へ送らず、URL に載せず、保存もしません。

---

© mitsulab（<https://mitsulab.jp>）。上の表の素材は、それぞれの出どころの条件に従います。
