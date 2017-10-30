# aed-sugito

埼玉県北葛飾郡杉戸町の AED 設置場所マップです。
自治体のオープンデータと Google Maps API との連携の練習として作ったものです。

作業の流れとしては大体こんな感じ。

・「埼玉県オープンデータポータル」から「【杉戸町】AED設置場所情報」のCSVファイルをダウンロード
・CSVファイルの文字コードを Shift-JIS から UTF-8 に変換
・CSVファイルからJSONファイルに変換
・jQueryでJSONファイルを読み取る
・Google Maps API で AED の設置場所を表示

以下のサイトを参考にさせていただきました。

埼玉県オープンデータポータル
https://opendata.pref.saitama.lg.jp/

CSV⇔JSONに変換してくれるファイルコンバーター・「sqlify」
http://kachibito.net/useful-resource/sqlify

Google Maps JavaScript API
Googleが提供する、Google Maps JavaScript APIを利用して、ウェブページに地図を表示させる方法を説明します。通常の埋め込み型の地図とは違い、コントローラの調整、マーカーや吹き出しを配置したりなど、機能が満載です。
https://lab.syncer.jp/Web/API/Google_Maps/JavaScript/

Google Maps APIを使って複数のマーカーと吹き出しを設置してみる
https://www.tam-tam.co.jp/tipsnote/javascript/post7755.html
