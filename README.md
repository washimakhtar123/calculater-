# calculater-
using function in c
#include<stdio.h>
char op;
int add(int a, int b)
{
	return a+b;
}
int subtract(int a, int b)
{
	return a-b;
}
int product(int a, int b)
{
	return a*b;
}
int division(int a, int b)
{
	return a/b;
}
int main()
{
	int a,b,sum ,sub ,mul ,Div;
	printf("enter two numbers:");
	scanf("%d%d",&a,&b);
	sum=add(a,b);
	sub=subtract(a,b);
	mul=product(a,b);
	Div=division(a,b);
	printf("sum:%d\n,subtract:%d\n,product:%d\n,and division%d\n",sum,sub,mul,Div);
	return 0;
}
printf("enter the opreators(+,-,*,/):");
scanf("%c",&op);
switch(op)
{
	case'+':
		printf("%d",add);
		break;
	case'-':
		printf("%d",sub);
		break;
	case'*':
		printf("%d",mul);
		break;
	case'/':
		printf("%d",Div);
		break;
	default:
		printf("invailed opreators:")
		
}
