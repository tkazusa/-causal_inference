# 因果推論まとめ
## 概念とか語彙とかもろもろ
- 相関関係：ある一方の変数の値が大きい時、他方の変数の値も大きい
- 因果関係：要因Xを変化させた時に要因Yも変化する
- 原因変数：原因を示す変数
- 結果変数(アウトカム)：結果を示す変数
- 介入/処置：要因を変化させること
- テスト群/コントロール群：施策を受けた群/受けなかった群
- 共変量：背景要因、つまり介入される以外の要因
- 割り当て(treat)：介入を受ける要因
- 交絡/交絡因子/疑似相関

## ドナルド・ルービンの因果モデル
- [central role of the propensity score in observational studies for causal effects | Biometrika | Oxford Academic
](https://academic.oup.com/biomet/article/70/1/41/240879)
- 潜在的なアウトカム(Potential outcome)

## 背景要因を揃えられるかどうか？
- 共変量の次元が大きくなると類似度の高いテスト/コントロール群を抽出する事例もある。->探したい
- ランダム化比較試験(RCT：Randomized Control Trial)に対して施策の割り当てができることが理想(A/Bテスト)
- テスト/コントロール群のデータに偏りが生じている場合

## 仮想現実(counterfactual)
- 
