# review-C-Langage
C言語のおさらい

## プリント出力
~~~c
#include<stdio.h>
int main(void){
  printf("Hello C Language\n");
  return 0;
}
~~~

## 四則演算
~~~c
#include<stdio.h>
int main(void){
  printf("1+5は%d",1+5);
  return 0;
}
~~~

## 変数
~~~c
#include<stdio.h>
int main(void){
  int a=5;
  int b[3]={2,3,7};
  int c[5][3]={{2,3,7},{8,44,22},{2,3,7},{1,4,7}};
  float d =000000000000.3;
  double e=0.0000000000000000000000000000000000000000555;
  char f='a';
  char g[]="This is strings"
  
  printf("a = %d\n",a);
  printf("b = %d\n",b[2]);
  printf("c = %d\n",c[3][2]);
  printf("d = %f\n",d);
  printf("e = %lf\n");
  printf("f = %c\n",f);
  printf("g = %s\n",g);
  
  return 0;
 }
~~~

## 関数
作成中
~~~c

~~~

## ポインタ
作成中
~~~c

~~~

