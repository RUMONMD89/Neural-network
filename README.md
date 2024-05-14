# Neural-network (ニューラルネットワーク)
## ニューラルネットワークとは
 人間の脳神経をモデル化したものでコンピュータ上に人間の脳神経回路を再現。
 脳細胞をモデル化した「単層パーセプトロン」を繋ぐ。
 * 4層以上連結したものをディープラーニングと呼びます。
 人間と同じように学習をすることで(機械学習)
 推論ができるようになる(手書き文字認識など)。
<img src="p1.png" height="400px" width ="700px">
### 
　IEPOCHは学習する回数を指定します。
(IEPOCH=1は学習データを1回学習します。)
###
RATIO
は学習用データの何割(0.0〜1.0)を
検証データとして使用するかを指定する。
(RATIO=0.1の時は10%を検証用データ、
残りの90%を学習データにする。)

・ ISEED
擬似乱数のシード値を指定します。
シード値を変更すると、生成される
乱数列(ランダムな数列)が変わります。
※python mnist4.py –s 1
のようにオプション引数「-s 値」で
設定することも可能です。
・IGRAPHIC
 1にするとグラフなどをウィンドウ表示します。
0にするとウィンドウは非表示となります。
※python mnist4.py –g 1
のようにオプション引数「-g 値」で
設定することも可能です。
