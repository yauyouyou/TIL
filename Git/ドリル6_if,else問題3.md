# 問題  
ECサイトのポイント付与サービスを考えます。
購入金額が999円以下の場合、3%のポイント
購入金額が1000円以上の場合、5%のポイント
このように付与されるポイントを出力するメソッドを作りましょう。

- ただし誕生日の場合はポイントが5倍になります。
- 誕生日の場合はtrue, 誕生日でない場合はfalseで表します。
- また、小数点以下をすべてのポイント計算が終わったあとに切り捨てましょう。
## ヒント  
小数点の切り捨ては、.floorメソッドを用います
```
irb(main):001:0> 3.1.floor
=> 3
irb(main):002:0> 3.9.floor
=> 3
```
## 出力例  
```
calculate_points(500, false) → ポイントは15点です
calculate_points(2000, false) → ポイントは100点です
calculate_points(3000, true) → ポイントは750点です
```
## 自分の解答  
```
def calculate_points(amount, is_birthday)
  if amount <= 999
    if is_birthday
      point = amount * 0.03 * 5
    else
      point =amount * 0.03
    end
  else amount >= 1000
    if is_birthday
      point = amount * 0.03 * 5
    else
      point = amount * 0.03
    end
  end

  puts point
end
```
## 模範解答  
```
def calculate_points(amount, is_birthday)
  if amount <= 999
    point = amount * 0.03
  else
    point = amount * 0.05
  end
  if is_birthday
    point = point * 5
  end
  puts "ポイントは#{point.floor}点です"
end
```
## 感想  
ifの中にifを入れるという条件分岐は正しくないのか調べたところ書けることは書けるらしい。だが、模範解答のコードのように分けて書いた方がコーディングする自分自身も見る人も分かりやすいと感じた。間違えてはいるが、考え自体は悪くはなかったと感じた。


