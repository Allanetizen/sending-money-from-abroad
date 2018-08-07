#include<stdio.h>
 main()
 

{
	int pin,amount,amount_received;
	float dollar=100.27;
	printf("Enter amount\n");
	scanf("%d",&amount);
	
	
	
	
    printf("Enter pin");
	scanf("%d",&pin);
	if(pin==1234)
	
	{amount_received=amount*dollar;
	printf("amount sent to Allan Kipkosgei Kibet is \n%d",amount_received);
	}
	else
	{printf("wrong pin!!!");}
	
	return 0;
}
