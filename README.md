
#include <stdio.h>

int main() {
    // Write C code here
    printf("Hello world");

    return 0;
}

#include <stdio.h>

int main() {
    //to calculate sum of two numbers 
    int a,b,s;
    printf("Enter the values of a and b\n");
    scanf("%d%d",&a,&b);
    s=a+b;
    printf("the sum of a and b is %d\n",s);
      return 0;
} 
#include <stdio.h>

int main() {
    // Write C code to calculate simple intrest
    float p,t,r,si;
    printf("enter the principle,time,rate of interest \n");
    scanf("%f%f%f",&p,&t,&r);
    si=(p*t*r)/100;
    printf("the simple interest:",si);

    return 0;
}

#include <stdio.h>

int main() {
    int a=5;
    float b;
    b=(float)a;//int to float 
    printf("%d\n",a);
    printf("%f\n",b);
    

    return 0;
}
// Write a c code to print your name , age and location 
#include <stdio.h>

int main() {
    char name;
     int age;
     char loc;
     printf("your name=Teju\n",name);
     printf("your age=18\n",age);
     printf("your location =clk\n",loc);
     return 0;
}
