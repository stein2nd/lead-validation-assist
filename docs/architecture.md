<!-- 
目的：「コード構造と責務」の明文化
 -->

1. 処理フロー図

```
Input CSV
↓
Normalization
↓
KEN_ALL Matching
↓
Scoring
↓
Output CSV
```

2. モジュール責務

* [オーケストレーション](../src/main.py)
* [パイプライン制御](../src/processing/processor.py)
* [KEN_ALL照合](../src/processing/matcher.py)
* [点数算出](../src/processing/scoring.py)
* [純粋関数](../src/utils/normalizer.py)

3. データフロー設計

* 元住所
* 正規化住所
* 郵便照合結果
* スコア
* 判定カテゴリ