# 問題  
「かつ」か「または」のどちらかを用いて  
- 1番目のSystem.out.println()がtrueと出力されるようにしてください
- 2番目のSystem.out.println()がfalseと出力されるようにしてください


- 「8 < 5」かつ「3 >= 2」の結果を出力してください
- 「8 < 5」または「3 >= 2」の結果を出力してください
- 「8 < 5」でない、の結果を出力してください（ただし、8 < 5を括弧で囲む必要があることに注意してください）

```
class Main {
  public static void main(String[] args) {
    // trueと出力されるようにしてください
    System.out.println(true || false);
    
    // falseと出力されるようにしてください
    System.out.println(false && true);
    
    // 「8 < 5」かつ「3 >= 2」の結果を出力してください
    System.out.println(8 < 5 && 3 >= 2);
    
    // 「8 < 5」または「3 >= 2」の結果を出力してください
    System.out.println(8 < 5 || 3>= 2);
    
    // 「8 < 5」でない、の結果を出力してください
    System.out.println(!(8 < 5));
    
  }
}
```
