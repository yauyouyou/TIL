## Rubyの繰り返しとの違い  
配列から要素を取り出す処理を繰り返し行うために、Rubyカリキュラムではeachメソッドを使用した。Javaにも似た機能を持つ「拡張for文」がある。Rubyのeachメソッドと用途は同じだが、記述の仕方は大きく異なる。  
## 拡張for文  
拡張for文を使用する際の構文  
```
for ( 要素を格納する変数宣言  :  配列あるいはArrayListの変数名) {
  取り出した要素を使用して行う処理
}
```
① 配列、あるいはArrayListから要素を1つ取り出す  
② 取り出した要素を変数に代入する  
③ {}内の処理を行う  
④ 配列、あるいはArrayListの要素数分だけ処理を繰り返す  

例  
```
class Main {
  public static void main(String[] args) {
    int[] scores = {1, 5, 10};

    for(int score : scores) {
      System.out.println(score);  
    }
  }
}
```
コードを実行すると、scoresという配列の要素として、「1, 5, 10」を代入しており、拡張for分によって取り出して出力できていることが分かる。  

ArrayListからも要素を取り出す場合も使い方は同様である。  
```
import java.util.ArrayList;

class Main {
  public static void main(String[] args) {
    ArrayList<Integer> scores = new ArrayList<Integer>();

    scores.add(1);
    scores.add(5);
    scores.add(10);

    for(int score : scores) {
      System.out.println(score);  
    }
  }
}
```
出力される結果は同じである。  

