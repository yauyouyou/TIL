# 問題  
非常に有名なプログラミングの問題です。1〜100までの数字をターミナルに出力してください。ただし、「3の倍数」のときは数字の代わりに文字列でFizzと、「5の倍数」のときはBuzz、3と5の倍数である「15の倍数」のときはFizzBuzzと出力してください。  
## 雛形  
```
def fizz_buzz
  # ここに処理を書き加えてください
end

fizz_buzz
```
## ヒント  
① 問題文で与えられている仕様を整理すると以下のようになります  
- 数字の1~100を出力する  
- 値が3の倍数のときだけ、"Fizz"という出力に置き換える  
- 値が5の倍数のときだけ、"Buzz"という出力に置き換える  
- 値が3と5の倍数のときだけ、"FizzBuzz"という出力に置き換える

②「〇〇の倍数」を導き出す時は剰余演算子を用いましょう

③条件を指定して繰り返し処理をする場合は、whileというメソッドを使いましょう  

## 自分の解答  
```
def fizz_buzz
  number = 1
  while number <= 100 do
    if number % 3 == 0
      puts "Fizz"
    elsif number % 5 == 0
      puts "Buzz"
    else number %  15 == 0
      puts "FizzBuzz"
    end
  end
end

fizz_buzz
```

## 模範解答  
```
def fizz_buzz
  num = 1
  while num <= 100 do
    if num % 15 == 0
      puts "FizzBuzz"
    elsif num % 3 == 0
      puts "Fizz"
    elsif num % 5 == 0
      puts "Buzz"
    else
      puts num
    end

    num = num + 1
  end
end

fizz_buzz
```
## 感想  
まず、numberをnumと記述できることと、whileメソッドを使うと繰り返し処理を施すことができることを学ぶことができた。自分の回答ではnum = num + 1に記述がなく、これでは繰り返しても次の数が計算できない。模範解答をすぐ気づけたのはよかった。
