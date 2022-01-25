## Part15 演習問題

pass文は何も処理を行わない文である。

```python
a = 1
if a == 1:
    pass

>>      ##出力には何も表示されない。
```

以下のcontinueを使ったコードをpassを使って同じ出力が出るように書き換えなさい。

```python
nums = [1,2,3,4,5]
for i in nums:
    if i == 1:
        continue
    print(i)

>> 2
   3
   4 
   5
```

(ヒント) passとcontinueの違いに関する問題。単にcontinueをpassに変えただけではうまくいかない。