# M2-D3
AIM:
Write a C program to print the given triangular alphabetic pattern using loop.

EXAMPLE :

INPUT:

5

OUTPUT :


aaaaa

aaaa

aaa

aa

a
PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=n;i>=1;i--)
    {
        for(j=i;j>=1;j--)
        {
            printf("%c",'a');
        }
         printf("\n");
    }
   
}
```
OUTPUT:
<img width="476" height="296" alt="image" src="https://github.com/user-attachments/assets/3d2f4be0-3a9b-4f29-b706-efe30238c40a" />
RESULT:
Thus the code run successfully!

