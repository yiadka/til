# Error Handling
## 今まで遭遇したエラー一覧
### 20231029
`TypeError unsupported operand`

### 20231023
### Scipyを使ったフィッティング
`TypeError: can't multiply sequence by non-int of type 'numpy.float64'`
#### 原因
浮動小数点が来てほしいのにシーケンスが来ているらしい。Numpyのarrayがそのまま投げられている？

#### 解決法
`list`を`np.array`にした。これだけだった。

#### 参照したもの
https://teratail.com/questions/364423
