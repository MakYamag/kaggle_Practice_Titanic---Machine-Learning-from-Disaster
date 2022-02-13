# 220213_kaggle_Practice_Titanic---Machine-Learning-from-Disaster
かの有名なTitanicコンペ練習用レポジトリ。

## Log
### [220213]
- ひとまずデータダウンロードし、欠損値補完、データ分割、標準化などやってみた後、パーセプトロンモデルで分類してみた。

#### nb001
- パーセプトロンモデルにて分類。
- 正解率 0.746
- 欠損値は*Age*にNaNが含まれていたので、平均値で補完。
- 扱いが分からなかった*Name*、*Ticket*、*Cabin*はひとまず特徴量から抜いた。
