## break  
繰り返し処理を終了するためには、条件をfalseにする以外に、breakを使って強制的に終了させる方法がある  
下図のようにif文などの条件分岐と組み合わせることで、任意の箇所で繰り返し処理を終了させることができる  
例  
```
for (int i = 1;i <= 10;i ++) {
  if (i >5) {
  }
  System.out.println(i);
}
```

## continue  
繰り返し処理を終了するbreakと違い、continueはその周の処理だけをスキップして、次の周を実行することができる  
continueもif文などと組み合わせて利用するのが一般的  
例  
```
int (int i = 1;i <= 10;i ++) {
  if (i % 3 == 0) {
    continue;
  }
  System.out.println(i);
}
```
