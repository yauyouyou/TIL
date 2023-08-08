## if文の使い方  
if文は以下のように記述する。  
```
if ( 条件式 ) {
  条件式を満たす時に実行する処理
}
```
Rubyとは以下の点が違う。  
- 条件式を（）で囲む必要があること  
- 行いたい処理を{}で囲む必要があること  
- elseは同様で、Rubyの「elsif」は、Javaでは「else if」と記述する  

基本的に使い方は同じで、以下のように記述する。  
```
if (条件A) { 
  // 処理A
} else if () {
  // 処理B
} else {
  // 処理C
}
```
- 条件Aが「真」の時は処理Aが実行される  
- 条件Aは「偽」で、条件Bが「真」の時は処理Bが実行される  
- 全ての条件が「偽」の時は処理Cが実行される

例  
```
class Main {
  public static void main(String[] args) {
    int value = 3;

    if (value > 0){
      System.out.println("値は正です"); 
    }else if (value < 0){
      System.out.println("値は負です"); 
    }else {
      System.out.println("値は0です"); 
    }
  }
}
```

