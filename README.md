
// **Write a program in c to print a simple calculator**

#include<stdio.h>

int main (){

    printf("Simple Calculator");
    
    char operator; 
    
    float num1,num2, result =0;
    
    printf("\n please enter an operator (+,-,*,/) :");
    
    scanf("%C",&operator);
    
    printf("/n Please enter the first  values for : num1 :");
    
    scanf ("%f",&num1);
    
    printf("/n Please enter the sceond values for : num2 :");
    
    scanf ("%f" ,&num2);
    
    
    switch(operator){
        case '+' :
        
        result = num1 + num2;
        
        break;

        
        case '-' :
        
        result = num1 - num2;
        
        break;
        
        case '*' :
        
        result = num1 *num2;
        
        break;
        
        case '/':
        
        result = num1 / num2;
        
        break;
        
        default :
        
        printf(" Invalid operator");
        
    }
    
    printf("/n the result of %2f %2c %.2f = %.2f" ,num1 , operator , num2 , result);
    return 0;
    
    }

    






