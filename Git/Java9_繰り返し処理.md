## Rubyの繰り返しとの違い  
配列から要素を取り出す処理を繰り返し行うために、Rubyカリキュラムではeachメソッドを使用した。Javaにも似た機能を持つ「拡張for文」がある。Rubyのeachメソッドと用途は同じだが、記述の仕方は大きく異なる。  
## 拡張for文  
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

