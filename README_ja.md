# データ ビジュアライゼーション パターン コレクション

[英語](https://github.com/ynunokawa/data-viz) | 日本語

チャート・マップ・イベントを用いたデータ ビジュアライゼーションのサンプル コレクションです。チャートは D3.js、地図は Leaflet あるいは ArcGIS API for JavaScript を使います。

データ可視化の手法として以下のような仮説をベースにアプリを作成します。

__(Map + Chart) * Event = Data Visualization ?__

## 地図

Leaflet・ArcGIS API for JavaScript の特長をもとにテーマによってライブラリを使い分けています。

__[Leaflet](http://leafletjs.com/)__ を使う理由

* シンプル
* ポピュラー
* 軽量
* サードパーティのライブラリに依存しない
* 豊富な[プラグイン](http://leafletjs.com/plugins.html)

__[ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/)__ を使う理由

* Esri [Web マップ](http://esrijapan.github.io/arcgis-dev-resources/create-webmap/)
* 地図とレイヤーを作成するためのコーディング不要
* 地図の状態を更新するためのコーディング不要
* レイヤーのスタイルを更新するためのコーディング不要
* レイヤーのスタイリングに利用できる豊富なクラス群 ([esri/renderers](https://developers.arcgis.com/javascript/jshelp/intro_bettermaps.html))

## チャート

__[D3.js](https://d3js.org/)__ を使う理由

* 好きだから！

## イベント

イベントとは…

* DOM イベント (click, hover..)
* フォームへの情報入力
* 時系列アニメーション
* など..

## ライセンス
MIT.
