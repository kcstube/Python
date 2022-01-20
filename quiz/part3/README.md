## Part3 演習問題

以下の2つのソースコードで挙動が異なるのはなぜでしょう？

```python
x = 1
y = x
x = 2
print("x = ", x)
print("y = ", y)

>> x = 2
   y = 1
```

```python
x = [1]
y = x
x[0] = 2
print("x = ", x)
print("y = ", y)

>> x = [2]
   y = [2]
```