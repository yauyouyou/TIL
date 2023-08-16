# 問題  
- 「真」を表す真偽値を出力してください  
- 「偽」を表す真偽値を出力してください  
- 比較演算子「==」を用いて、12 / 4と3を比較した結果を出力してください  
- 比較演算子「!=」を用いて、12 / 4と3を比較した結果を出力してください  
- boolean型の変数boolを定義し、比較演算子「==」を用いて、3 * 9と27を比較した結果を代入してください。変数boolの値を出力してください  

## 自分の解答
```
class Main {
  public static void main(String[] args) {
    // 「true」を用いて、「真」を表す真偽値を出力してください
    System.out.println(true);
    
    // 「false」を用いて、「偽」を表す真偽値を出力してください
    System.out.println(false);
    
    // 「==」を用いて、値を比較した結果を出力してください
    System.out.println(12 / 4 == 3);
    
    // 「!=」を用いて、値を比較した結果を出力してください
    System.out.println(12 / 4 != 3);
    
    // 変数を定義し、値を比較した結果を代入してください
    boolean bool = true;
    System.out.println(3 * 9 == 27);
    
    // 変数boolの値を出力してください
    System.out.println(bool);
    
  }
}
```

## 解答  
```
class Main {
  public static void main(String[] args) {
    // 「true」を用いて、「真」を表す真偽値を出力してください
    System.out.println(true);
    
    // 「false」を用いて、「偽」を表す真偽値を出力してください
    System.out.println(false);
    
    // 「==」を用いて、値を比較した結果を出力してください
    System.out.println(12 / 4 == 3);
    
    // 「!=」を用いて、値を比較した結果を出力してください
    System.out.println(12 / 4 != 3);
    
    // 変数を定義し、値を比較した結果を代入してください
    boolean bool = 3 * 9 == 27;
    
    // 変数boolの値を出力してください
    System.out.println(bool);
    
  }
}
```

下記の間違いは変数を定義し、値を比較した結果を代入するの意味を理解できていなかった
boolean bool = true;
System.out.println(3 * 9 == 27);
