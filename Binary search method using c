#include<stdio.h>

int main()
{
	int i,key,A[100],n,flag=0,mid,First,Last;
	
	printf("enter n");
	scanf("%d",&n);
	
	printf("\nEnter the array element");
	for(i=0;i<n;i++)
		scanf("%d",&A[i]);
		
	printf("\nenter the key element");
	scanf("%d",&key);
	
	First=0;
	Last=n-1;
		
	while(First<=Last)
	{
		mid=(First+Last)/2;
		if(A[mid]==key)
		{
			flag=1;
			break;	
		}
		else if (A[mid]>key)
				Last=mid-1;
		else if (A[mid]<key)
				First=mid+1;
	}
	if(flag==0)
		printf("\nKey element NOT FOUND");
	else
		printf("\nKey element FOUND");
	return 0;
}
