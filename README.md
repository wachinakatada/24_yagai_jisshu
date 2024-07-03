# 24_yagai_jisshu
##### 2024年度・前期「生物学野外実習」理学部海洋自然科学科
##### https://tiglon.jim.u-ryukyu.ac.jp/portal/Public/Syllabus/SyllabusSearchStart.aspx?lct_year=2024&lct_cd=401194001&je_cd=1
##### @琉大熱生研・西表研究施設

##### 2024年7月5日・琉大周辺で見られるチョウの種多様性の評価


##### 1. R環境の導入とveganのインストール
今回は`webR`を利用します。

1.1. WebRのデモ版 https://webr.r-wasm.org/latest/ をブラウザで開く。

1.2. `vegan`をインストールする。
```
> library(vegan)
```

`vegan`を読み込めないので、ダウンロードするか聞かれるので、`Yes`
```
Failed to load package "vegan". Do you want to try downloading it from the webR binary repo? 

1: Yes
2: No

Selection: Yes
Downloading webR package: permute
Downloading webR package: lattice
Downloading webR package: MASS
Downloading webR package: cluster
Downloading webR package: nlme
Downloading webR package: Matrix
Downloading webR package: mgcv
Downloading webR package: vegan
Loading required package: permute
Loading required package: lattice
This is vegan 2.6-6.1
```
