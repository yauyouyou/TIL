# メソッドの使用（引数がある場合）  
メソッドで引数を使う方法は、Rubyの場合と似ている  

例  
```
class Main {
  public static void main(String[] args) {
    var answer = square(5);
    System.out.println(answer);
  }

  public static int square(int number){
    return number * number;
  }
}
```

```
メソッドの定義
public static int square(int number){
  return number * number;
}
```
- 仮引数は、「int number」となっている
- Rubyとは違い、変数名「number」だけでなく、受け取る値のデータ型（今回はint）を指定する必要がある    
- なお、このメソッドの返り値は整数型です。そのため、メソッド名の前に「int」と記述していることに注意

メソッドの実行は以下のように記述  
```
var answer = square(5);
```
「square(5)」と、メソッドsquare()を実行する際に、引数として「5」を指定している  
引数の使い方はRubyの場合とほぼ同じで、仮引数にデータ型の指定が必要なことだけが異なるということになる  
