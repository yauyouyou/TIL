# 問題  
- 「else if」を用いて、変数numberが20より小さいとき、10以上、20より小さいと出力してください  
- どちらでもないとき、20以上と出力してください

```
class Main {
  public static void main(String[] args) {
    int number = 12;
    
    // numberが20より小さいとき、どちらでもないときの条件分岐を追加してください
    if (number < 10) {
      System.out.println("10より小さい");
    } else if (20 > number) {
      System.out.println("10以上、20より小さい");
    } else {
      System.out.println("20以上");
    }
    
  }
}
``` 
