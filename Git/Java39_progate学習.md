# 問題  
- 文字列を要素に持つ配列用の変数languagesを定義し、{"Ruby", "PHP", "Python"}を代入してください  
- インデックス番号が「1」の要素を出力してください  
- インデックス番号が「1」の要素を、Javaで上書きしてください  
- もう一度インデックス番号が「1」の要素を出力してください

```
class Main {
  public static void main(String[] args) {
    // 変数languagesを定義し、配列を代入してください
    String[] languages = {"Ruby", "PHP", "Python"};
    
    // インデックス番号が「1」の要素を出力してください
    System.out.println(languages[1]);
    
    // インデックス番号が「1」の要素を「Java」で上書きしてください
    languages[1] = "Java";
    
    // インデックス番号が「1」の要素を出力してください
    System.out.println(languages[1]);
    
  }
}
```
