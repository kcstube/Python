## Part4 演習問題

1. シングルクォートの中でシングルクォートを含む文字列を扱う方法を考えなさい。

2. 'C:\some\name'という文字列を表示させなさい。(ヒント: 以下のようにやってしまうと\で特殊文字としてnがエスケープされてしまいます。)

```python
print('C:\some\name')  #\nで改行される

>> 'C:\some
    ame
```

Keyword: raw string
