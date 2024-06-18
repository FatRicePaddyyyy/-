# データ分析
Kaggleなどのデータを用いてデータ分析をします。
### 宇宙版タイタニック
LightGBMというモデルを変更するなく、特徴量エンジニアリングとアンサンブル学習によってモデルの精度を向上させていきます。


1_EDAipynb.ipynb : EDAをします<br>
2_normal.ipynb : とくに工夫をしないLightGBMです<br>
3_欠損値.ipynb : 欠損値を中央値や最頻値で埋めます<br>
4_LightGBMによる欠損値.ipynb : LightGBMで欠損値を埋めます<br>
5_特徴量追加.ipynb : 列から新しく特徴量を作り出します<br>
6_クロスバリデーション.ipynb : クロスバリデーションにより、同じモデルで複数回学習させることで精度を上げます<br>
7_結果の解釈:SHAP値.ipynb : SHAP値により、モデルを解釈します<br>
