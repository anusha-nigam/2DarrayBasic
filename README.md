# 2DarrayBasic
//read a matrix and display it 
#include<stdio.h>
main(){
    int i,j,k,m,n,arr[100][100];

    printf("enter the dimensions for arr: ");
    scanf("%d %d",&m,&n);

    printf("enter the elements ");

    for(i=0;i<m;i++){
        for(j=0;j<n;j++){
            scanf("%d",&arr[i][j]);

        }

    }
     for(i=0;i<m;i++){
        for(j=0;j<n;j++){
            printf("%d ",arr[i][j]);

        }
            printf("\n");
    }
}
