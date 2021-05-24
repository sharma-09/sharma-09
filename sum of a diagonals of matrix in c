#include<stdio.h>
int main(){
   int i, j, row,col;
   int sum=0;
   printf("Enter the number of rows and column = ");
   scanf("%d %d",&row,&col);
   int a[row][col];
   printf("Enter the matrix-\n");
   for(i=0; i<row; i++) {
      for(j=0;j<col;j++) {
         scanf("%d", &a[i][j]);
      }
   }
   for(i=0; i<row; i++) {
      for(j=0;j<col;j++) {
         if(i==j){
            sum=sum+a[i][j];
         }
      }
   }
   printf("The sum of diagonals of a matrix = %d\n",sum);
   return 0;
}
