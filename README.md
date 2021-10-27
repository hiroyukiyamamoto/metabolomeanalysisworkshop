# Rを用いたメタボロームデータ解析: Metabolome data analysis using R

## 要旨

BioconductorパッケージXCMSを用いた、メタボロミクスにおける質量分析データ処理の手順を簡単に紹介する。次に、Rパッケージloadingsを用いた多変量解析の手順を紹介する。loadingsパッケージは、メタボロームデータを可視化するだけでなく、主成分負荷量やPartial last squares 負荷量とそれらの統計的仮説検定を用いて、有意な代謝物を選択することが出来る。

I will briefly introduce the procedure for mass spectrometry data processing in metabolomics using the R Bioconductor package “XCMS”. And, I will also introduce the procedure for multivariate analysis using R package “loadings”. The “loadings” package can not only visualize metabolome data, but also select significant metabolites using Principal component loadings, Partial least squares loadings and their statistical hypothesis testing.

## 使用するR/Bioconductorパッケージ

- 質量分析データ処理：<a href="https://bioconductor.org/packages/release/bioc/html/xcms.html">xcms</a> (Bioconductor)
- 多変量解析(PCAとPLS)：<a href="https://cran.r-project.org/web/packages/loadings/index.html">loadings</a> (CRAN)

## タイムスケジュール

- 全体の説明 (<a href="https://github.com/hiroyukiyamamoto/metabolomeanalysisworkshop/blob/master/vignettes/%E7%99%BA%E8%A1%A8%E8%B3%87%E6%96%99.pdf">発表資料</a>) (15分)
- <a href="https://bioconductor.org/packages/release/bioc/html/xcms.html">xcms</a>による質量分析データ処理(10分)
- <a href="https://cran.r-project.org/web/packages/loadings/index.html">loadings</a>パッケージによる主成分分析と主成分負荷量を用いた代謝物の選び方(15分)
- <a href="https://cran.r-project.org/web/packages/loadings/index.html">loadings</a>パッケージによるPartial least squares(PLS)とPLS負荷量を用いた代謝物の選び方(20分)

## 資料

- <a href="https://hiroyukiyamamoto.github.io/metabolomeanalysisworkshop">Webサイト</a>
- <a href="https://github.com/hiroyukiyamamoto/metabolomeanalysisworkshop/blob/master/vignettes/%E7%99%BA%E8%A1%A8%E8%B3%87%E6%96%99.pdf">発表資料(pdfファイル)</a>

## 連絡先

- 山本博之 h.yama2396@gmail.com
