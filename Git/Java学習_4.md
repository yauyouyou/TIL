# 型推論  
型推論を利用した変数の宣言方法  
```
var 変数名 = 値
```
例  
```
class Main {
  public static void main(String[] args) {
    int radius;
    radius = 5;
    System.out.println(radius * radius * 3.14);
  }
}
```
上記のコードに型推論を使用  
```
class Main {
  public static void main(String[] args) {
    var radius = 5;
    System.out.println(radius * radius * 3.14);
  }
}
```
- 結果は同じで、「78.5」
- 上記のようにvarを使用すると、代入する値（今回の例では5）からデータ型を推論してくれるため、int型であるという宣言が不要になる。
