# Matrix
#include<stdio.h>
int main()
{
   int disp[3][3];
   int i, j;
   for(i=0; i<3; i++) {
      for(j=0;j<3;j++) {
         printf("enter value for disp[%d][%d]:", i, j);
         scanf("%d", &disp[i][j]);
      }
   }
    printf("three Dimensional array elements:\n");
   for(i=0; i<3; i++) {
      for(j=0;j<3;j++) {
         printf("%d ", disp[i][j]);
         if(j==3){
            printf("\n");
         }
      }
   }
   return 0;
}
