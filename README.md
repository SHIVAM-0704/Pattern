# Pyramid
#include<stdio.h>

int main()

{

              int n,i,space,j;

              n=5;

              for(i=1;i<=5;i++)

              {

                           for(space=10;space>i;space--)

                           {

                           printf(" ");

                           }

                   for(j=1;j<=i;j++)

                  {

                           printf("%d ",j);

                  }

              printf("\n");

              }

              return 0;

}
