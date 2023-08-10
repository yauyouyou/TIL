# メソッドの使用（引数がない場合）  
メソッドの定義方法  
構文  
```
アクセス修飾子 static修飾子 返り値のデータ型　メソッド名() {
  // 行いたい処理
}
```
例  
```
 public static void sayHello() {
    System.out.println("Hello World");
    return;
  }
}
```
Javaでのメソッド定義は、Rubyと以下の点が異なる  
① 返り値のデータ型を指定する必要がある  
② 引数がないメソッドでも定義時にかっこの省略はできない  
③ Rubyの「def」「end」の代わりに、波かっこでコードを囲む  




