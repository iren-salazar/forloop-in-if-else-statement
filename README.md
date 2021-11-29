# forloop-in-if-else-statement
printing even or odd for 10 times in for loop in if else statement

#include<iostream>
using namespace std;

int main()
{
   int i,n=10;
   
   for (i= 1;i <=n; i++){
       
       if (i)
           printf ("%4d [Even]\t, i);
       else
       
       if (n%1=0)
          printf ("%4d [Odd]\t", i);
   }
   
   return 0;
}
     /*output:
     
      1 [Even]
      2 [Even]
      3 [Even]
      4 [Even]
      5 [Even]
      6 [Even]
      7 [Even]
      8 [Even]
      9 [Even]
     10 [Even]
     */
