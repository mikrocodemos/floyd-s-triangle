# floyd-s-triangle
	#include<stdio.h> 
		int main()
		{ 
		int i, j,n,a=1; 
		printf("enter no of rows");
	        scanf("%d",&n);
		for(i=0;i<n;++i)
		{ 
		  for(j=0;j<=i;++j)
		   { 
		     printf(" %d ",a); 
		     a++;
		   } 
		     printf("\n"); 
		   } 
		return 0; 
		}

