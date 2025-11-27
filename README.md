# 第27回図書館総合展　国立国会図書館主催フォーラム付録ツール
次世代デジタルライブラリーからのテキストデータのダウンロードと新旧かな判定ツール

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ndl-lab/NextDLAnalyzer/blob/master/disedigietextdownloader.ipynb)

TF-IDF特徴量とLightGBMによる、テキストデータの旧かな/新かな自動判定機能を有した、ダウンローダです。

このツールは
[第27回図書館総合展　国立国会図書館主催フォーラム「NDLラボの公開ツールを使ってみよう！—NDL古典籍OCR-Liteや古典籍・近代自筆資料への全文検索が広げる資料探索の可能性—」](https://www.ndl.go.jp/jp/event/events/lff2025.html)
のために作成したものです。

## 使い方
Open in Colabボタンを押すとGoogle Colabotatoryノートブック（外部サイト）が開く。

次のUIが表示されるので、検索・取得したい内容を入れる。


<img src="./assets/cap1.png" width="600">

上部に表示されるバーから、「すべてのセルを実行」ボタンを押す。

<img src="./assets/execute.png" width="600">

次の警告が出るので、「このまま実行」ボタンを押す。

<img src="./assets/execute2.png" width="600">

しばらく待つと上部から順番にコードが実行される。

次の「テキストDL」ボタンを押すと、取得したテキストデータをダウンロードできる。

<img src="./assets/cap2.png" width="600">

次の「判定結果DL」ボタンを押すと、機械学習モデルによる新かな旧かな判定結果を含めた表をダウンロードできる。

<img src="./assets/cap3.png" width="600">
