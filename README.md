#include <stdio.h>
int main()
{
   int i=65;
   switch(i)
   {
       case 65:
       printf("integer 65");
       break;
       case 'A':
       printf("char 65");
       break;
       default:
       printf("bye");
   }
    return 0;
}
    
//output: compilation error
