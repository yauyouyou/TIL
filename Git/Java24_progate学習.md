## else  
ifとelseを組み合わせると、「もし〜なら◯◯、そうでなければ△△」という条件分岐が可能になる  
例  
```
int x 20:
if (x < 30) {
  System.out.println("xは30より小さい")
} else {
  System.out.println("xは30以上")
}
```
結果  
xは30より小さい  

## else if  
ifとelse if、elseを組み合わせると、「もし〜なら◯◯、そうではなくてもし××なら△△、どちらでもない場合は□□」という条件分岐を実現できる  
例  
```
int x = 25;
if(x >= 30) {
  System.out.println("xは30以上")
} else if (x >20) {
  System.out.println("xは20より大きく、30より小さい");
} else {
  System.out.println("xは20以下");
}
```
結果  
xは20より大きく、30より小さい
