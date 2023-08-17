## default  
switch文では、どのcaseとも一致しなかったときに実行する処理を、defaultに指定することができる、これはif文のelseに似ている  
例  
```
int n = 0;
switch (n) {
  case 1:  ... ➀変数nが一致しない
    System.out.println("");
    break;
  case 2:  ... ➁変数nが一致しない
    System.out.println("");
    break;
  default:  ... ➂defaultの処理を実行する
    System.out.println("");
    break;
}
```
