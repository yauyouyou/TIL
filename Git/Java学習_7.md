## リストについて  
リストは、Rubyの配列と似たデータ管理の仕組みである。  
以下の特徴がある。  
- 要素を順序づけて管理する  
- 要素を事後的に追加したり削除できる  

また、Javaのリストには、以下の2種類がある。  
- ArrayList  
- LinkedList  
## ArrayListについて  
ArraListは「可変長配列」を使用するための仕組みである。可変長配列とは、文字通り長さ（要素数）を変更できる配列のこと。  
Rubyの配列は可変長なので、Javaの配列よりもArrayListの方が性質や使い方が近いものとなっている。  
## ArrayListの使い方  
① ライブラリをインポートする  
② ArrayListの宣言を行う  
③ ArrayListに値を代入する  
④ ArrayListから要素を取り出す  
### ライブラリをインポートする  
ArrayListを使用する際は、ライブラリのインポートが必要である。    
インポートするには、ファイルの冒頭に以下の記述を行う。    
```
import java.util.ArrayList;
```
### ② ArrayListの宣言を行う  
ArrayListの宣言と初期化は以下のように行う。  
```
ArrayList<データ型> scores = new ArrayList<データ型>();
```
例  
```
ArrayList<Integer> scores = new ArrayList<Integer>();

以下のように省略できる
ArrayList<Integer> scores = new ArrayList<>();
```

