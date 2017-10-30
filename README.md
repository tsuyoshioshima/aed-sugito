# aed-sugito

埼玉県北葛飾郡杉戸町の AED 設置場所マップです。
自治体のオープンデータと Google Maps API との連携の練習として作ったものです。

## 作業の流れ

- 「埼玉県オープンデータポータル」から「【杉戸町】AED設置場所情報」のCSVファイルをダウンロード
- CSVファイルの文字コードを Shift-JIS から UTF-8 に変換
- CSVファイルからJSONファイルに変換
- jQueryでJSONファイルを読み取る
- Google Maps API で AED の設置場所を表示

## 参考サイト

- 埼玉県オープンデータポータル
https://opendata.pref.saitama.lg.jp/

- CSV⇔JSONに変換してくれるファイルコンバーター・「sqlify」
http://kachibito.net/useful-resource/sqlify

- Google Maps JavaScript API
https://lab.syncer.jp/Web/API/Google_Maps/JavaScript/

- Google Maps APIを使って複数のマーカーと吹き出しを設置してみる
https://www.tam-tam.co.jp/tipsnote/javascript/post7755.html
