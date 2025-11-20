# NextDLAnalyzer
次世代デジタルライブラリーからのテキストデータのダウンロードと分析ツール

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ndl-lab/blob/master/disedigietextdownloader.ipynb)

TF-IDF特徴量とLightGBMによる、テキストデータの旧かな/新かな自動判定機能を有した、ダウンローダです。

## 使い方
Open in Colabボタンを押すとGoogle Colabotatoryノートブックが開く。

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
