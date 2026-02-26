<!-- 
目的：「スコア算出ロジック」の数式化
 -->

1. 判定項目

* 都道府県一致
* 市区町村一致
* 町域一致
* 番地一致
* URL疎通
* 法人番号存在

2. 点数配分

```
prefecture: 30
city: 30
town: 20
address_detail: 10
url_alive: 10
```

3. 判定区分

```
80-100 : High confidence
50-79  : Medium
0-49   : Low
```

4. 将来拡張項目

* Google検索一致
* 地理距離一致