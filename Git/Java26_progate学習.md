## switch文  
- switch文は条件の値がcaseの値と一致するとき、処理が実行される  
- switch文は構文が少し複雑、caseの後ろのコロン（:）などは忘れがちなので注意  
例  
```
int n = 1;
switch (n) {
  case 1:
    System.out.println("大吉です");
    break;
  case 2;
    System.out.println("吉です");
    break;
}
```

## break  
- breakとはswitch文を終了する命令である  
- breakがないと、合致したcaseの処理を行った後、その次のcaseの処理も実行してしまう  
- 意図せぬ処理が起こってしまうため、switch文を使うときにはbreakを忘れないように気をつける
例  
```
int n = 1;
switch (n) {
  case 1:
    System.out.println("大吉です");
    [breakがない場合空白]
  case 2:
    System.out.println("吉です");
    break;
}
```
