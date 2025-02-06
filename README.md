# man-whitney

# 概要

本プロジェクトでは、マンホイットニーU検定を使用して異なるグループ間の統計的有意差を評価するPythonスクリプトを提供します。本スクリプトはExcelデータを読み込み、各グループ間の統計的比較を行い、結果をCSVに保存します。

# 使用技術

Python 3

Pandas

SciPy

# 使用方法

1. ファイル名とシート名の指定

   
excel_file = 'マンホイットニー.xlsx' 

sheet_name = '甘味'       


2. スクリプトの実行

# 出力データ

mannwhitney_results_with_significance.csv

各グループ間のマンホイットニーU検定結果（統計値、p値、有意差の有無）をまとめたCSVファイル。


# 著者

近畿大学 理工学部 情報学科 システムデザイン論研究室 田中真矢
