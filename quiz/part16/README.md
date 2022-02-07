## Part16 演習問題

以下のソースコードをそれぞれ実行して、普通のfor文とリスト内包表記の実行速度を比較しなさい。

```python
%%timeit
case1 = []
for i in range(10000):
  case1.append(i)
case1
```

```python
%%timeit
case2 = [j for j in range(10000)]
case2
```

実行速度に関する考察は以下の記事に書いてある。要約すると、append関数の呼び出し部分でオーバーヘッドがかかってfor文の方が遅い。

[https://qiita.com/y__sama/items/a2c458de97c4aa5a98e7](https://qiita.com/y__sama/items/a2c458de97c4aa5a98e7)