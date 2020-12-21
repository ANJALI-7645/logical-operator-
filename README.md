# include<stdio.h>
int main()
{
int ram,shyam,ajay;
printf("enter the age of ram ,shyam and ajay");
if(ram<shyam && ram<ajay)
printf("ram is the youngest one");
else if(shyam<ram && shyam<ajay)
printf(" the youngest one is shyam");
else if( ajay<ram && ajay<shyam)
printf("the youngest one is ajay");
return 0;
}
