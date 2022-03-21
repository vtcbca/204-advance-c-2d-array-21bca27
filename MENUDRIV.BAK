/* WRP manubriven program perform following task using diffent function category
1:Prime
2:Palindeom
3:Reverse
4:print even number till n
5:Exit                          */
#include<stdio.h>
#include<conio.h>
void prime();
void palindrom(int);
int reverse();
int even(int);
int menu();
void main()
{
	int n,c,a,d;
	char yn;
	clrscr();
	do
	{
	c=menu();
	switch(c)
	{
	case 1:
		prime();
		break;
	case 2:
		palindrom(a);
		break;
	case 3:
		d=reverse();
		printf("Reverse number is %d",d);
		break;

	case 4:
		exit();
	default:
		printf("Invalid number");
	}
	printf("\n\n\t do you want to run agian?(Yes=Y/y,No=N/n):");
	flushall();
	scanf("%c",&yn);
	}while(yn=='Y'||yn=='y');
	getch();
}
int menu()
{
	int c;
	printf("\t\tMENU");
	printf("\n---------------------------------------");
	printf("\n 1:Prime \n 2:Palindrom \n 3:Reverse number \n 4:Even number serise \n 5:Exit");
	printf("\n---------------------------------------");
	printf("\nEnter your choice:");
	scanf("%d",&c);
	return c;
}
void prime()
{
	int n,count=0,i;
	printf("Enter value of n:");
	scanf("%d",&n);
	for(i=2;i<n;i++)
	{
		if(n%i==0)
		{
			count=1;
			break;
		}
	}
	if(count==1)
		printf("Enter number is not prime:");
	else
		printf("Enter number is prime:");
}
void palindrom(int n)
{
	int a,b,t,p=0;
	printf("Enter value of a:");
	scanf("%d",&a);
	for(t=a;a>0;a=a/10)
	{
		b=a%10;
		p=b+p*10;
	}
	if(t==p)
		printf("\n Enter number is palindrom");
	else
		printf("\n Enter number is not palindrpm");
}
int reverse()
{
	int x,y,c,s=0;
	printf("Enter value of x:");
	scanf("%d",&x);
	c=x;
	while(x>0)
	{
		y=x%10;
		s=y+s*10;
		x=x/10;
	}
	return(s);
}






