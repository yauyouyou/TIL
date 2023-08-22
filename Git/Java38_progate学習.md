## 配列の要素を上書きする  
- 配列の各要素は変数のようなもの  
- 下図のように、特定の要素に値を代入することで、要素を上書きすることが可能
```
String[] names = {"John","Kate","Bob"};

System.out.println(names[0]);
names[0] = "William";    ←0番目の要素を上書き
System.out.println(names[0]);
```

## 要素の上書きにおける注意点  
- 配列では存在しない要素に値を代入することはできないので注意
