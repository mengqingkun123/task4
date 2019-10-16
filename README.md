#include<stdio.h>
int main()
{
	float data1,data2;
	char op;
	float result;
	
	scanf("%f%c%f",&data1,&op,&data2);
	
	switch(op){
		case 'x':
			result = data1 + data2;
			break;
		case '-':
			result = data1 - data2;
			break; 
		case '*':
			result = data1 * data2;
			break;
		case '/':
			result = data1 / data2;
			break;
		default:
			printf("error"); 
	}
	
	printf("result%f",result);
	

}
