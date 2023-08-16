## 真偽値とは  
真偽値のデータ型はboolean型  
変数定義  
```
boolean 変数名 = true(or false);
```

## 比較演算子  
比較演算子とは、値を比較するための記号で、比較した結果は真偽値（trueかfalse）になる  
「x == y」はxとyが同じかどうかを比較し、同じであればtrue、違っていればfalseとなります。また「x != y」はその逆になる  

例  
```
6 + 2 == 5 ... false
6 + 2 != 5 ... true
6 / 3 == 2 ... true
6 / 3 != 2 ... false
```

## 真偽値の出力  
真偽値も出力することができる  
ただし、trueやfalseはダブルクォーテーションで囲んではいけない  
比較演算子の結果は真偽値になり、コンソールにも真偽値が出力される  
```
コード　　　　　　　　　　　　コンソール

System.out.println(true);  ...true
System.out.println(false);  ...false
System.out.println(6 + 2 == 5);  ...false
System.out.println(6 + 2 != 5);  ...true
```
