# 問題  
以下の要件を満たす in1to10メソッドを実装しましょう  
- 第一引数のnumが1以上かつ10以下の範囲であればTrueを出力すること
- 第二引数のoutside_modeがTrueの場合は、第一引数numが条件範囲外でもTrueを出力すること
- それ以外はFalseを出力すること  
## 雛形
```
def in1to10(num, outside_mode)
  # ここに条件式を記述する
end

# 呼び出し例
in1to10(5,false)
in1to10(11,false) 
in1to10(11,true)
```

## 解答  
```
def in1to10(num, outside_mode)
  if (num >= 1 && num <= 10) || outside_mode
    puts "True"
  else
    puts "False"
  end
end
```

## 感想  
- ヒント
```
# aもbもtrueの場合にtrue
a && b 

# aかbのどちらかがtrueの場合にtrue
a || b 
```
上記のヒントを参考にしながら解くことができた。ヒントの記述はアプリケーションのログインの有無でページにとべないようにするなどの複雑な設定をするときに役に立つと感じた。
