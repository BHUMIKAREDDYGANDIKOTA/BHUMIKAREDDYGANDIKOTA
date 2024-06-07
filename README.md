#include <stdio.h>  
#include <conio.h>      
main()  
{  
printf (" It is a main() function ");  
int fun2();   
printf ("\n Finally exit from the main() function. ");  
}  
void fun1()  
{  
printf (" It is a second function. ");  
printf (" Exit from the void fun1() function. ");  
}  
int fun2()  
{   
void fun1();  
printf (" It is a third function. ");  
printf (" Exit from the int fun2() function. ");  
return 0;  
}
