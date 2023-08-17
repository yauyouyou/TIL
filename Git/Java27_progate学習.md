# 問題  
switch文を用いて、int型の変数nに関する条件分岐を行いましょう  
変数nが、  
1のとき、大吉です  
2のとき、吉です  
とそれぞれ出力してください  

```
class Main {
  public static void main(String[] args) {
    int n = 1;
    
    // switch文を用いて、変数nの値に応じて条件分岐をしてください
    switch (n) {
      case 1:
        System.out.println("大吉です");
      case 2:
        System.out.println("吉です");
        break;
    }
  }
}
```
