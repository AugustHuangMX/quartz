#C_language #permanent 
Example：数数几位数
示例代码：
```c
int x;
int n=0;
scanf("%d",&x);
n++;
x/=10;
while(x>0){
	n++;
	x/=10;
}
printf("%d\n",n);
return 0;
```
 ![[卢曼笔记盒/附件/截屏2023-02-19 19.02.07.png|500]]
 循环体内要有改变条件的机会，否则会陷入无尽的循环捏
