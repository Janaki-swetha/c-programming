clude<stdio.h>
#include<string.h>
int main()
{
	char str[100];
	int i;
	char tolower;
    char toupper;
	printf("enter string:");
	gets(str);
	for(i=0;str[i]!='\0';i++)
	{
		if((i%2)==0)
        tolower(str[i]);
        else
        toupper(str[i]);
	}
	printf("%s",str);
	retincludeurn 0;
}
