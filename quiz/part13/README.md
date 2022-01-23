## Part13 演習問題

(1) 次のソースコードを実行し、文字列がイテラブルなオブジェクトであるかどうかを確認しなさい。

```python
word = 'cat'
for letter in word:
    print(letter)
```

(2) 辞書、

```python
color = {"red": 1, "blue": 2, "yellow": 3}
```

をイテラブルなオブジェクトとして、for文を使ってkeyとvalueを順番に取り出すコードを書きなさい。

出力例

```python
red 1
blue 2
yellow 3
```

(ヒント) .items()関数を用いる。