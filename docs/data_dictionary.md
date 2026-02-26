<!-- 
目的：「出力CSVの列定義」の明文化
 -->

| 列名 | 型 | 説明 |
| --- | --- | --- |
| original_address | string | 元所在地 |
| normalized_address | string | 正規化住所 |
| kenall_match_flag | bool | 町域一致 |
| address_score | int | 住所スコア |
| total_score | int | 総合スコア |
| validation_level | string | high/mid/low |
