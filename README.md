\\predefine-and-postdifine
#include<stdio.h>
#include<conio.h>
void main(){
int i;
clrscr();
i = 1;
printf("%d\n",i);\\1
printf("%d\n",++i);\\2
printf("%d\n",++i);\\3
printf("%d\n",i++);\\3
printf("%d\n",i++);\\4
getch();
}
