
#include<stdio.h>
void input(char*);
void display(char*);
int main()
{char str[10];
input(&str);
display(&str);
return 0;
}
void input(char *s)
{printf("\n enter a string :");
scanf("%s", s);
}
void display(char *s)
{
printf("\n %s",s);
}

