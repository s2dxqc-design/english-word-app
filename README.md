# iPhone英単語学習アプリ

## CSV形式
Excelで次の2列を作成し、UTF-8 CSVで保存します。

word,meaning
engine,エンジン
calibration,適合・調整

## iPhoneで使う
このフォルダーをHTTPS対応のWebサーバー（GitHub Pages、SharePointの静的サイト等）に配置し、Safariで index.html を開きます。共有ボタンから「ホーム画面に追加」を選ぶとアプリ風に起動できます。

## 動作
- 分からない回数が多い単語ほど出題確率が上がります。
- 正答率と学習履歴は端末内（localStorage）に保存されます。
- 発音はiPhoneの音声合成を使用します。
- CSVを再読込しても、同じ単語の履歴は維持されます。
