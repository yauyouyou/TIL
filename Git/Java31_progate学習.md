# 問題  
- 10から1までカウントダウンするプログラムを書いてみましょう  
- while文を用いて、変数numberが「0より大きい」場合に繰り返す、繰り返し処理を作ってください  
- while文の処理を書いていきます。while文の中で、・変数numberの値を出力してください。・変数numberから1を引いてください

```
class Main {
  public static void main(String[] args) {
    int number = 10;
    
    // while文を用いて、numberが0より大きい場合に繰り返す、繰り返し処理を作ってください
    while (number > 0) {
      System.out.println(number);
      number --;
    }
    
  }
}
```
