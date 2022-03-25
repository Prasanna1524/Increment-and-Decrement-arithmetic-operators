# Increment-and-Decrement-arithmetic-operators

      #include <stdio.h>

      int main()
      {
          int a = 10, res;

          // post-increment example:
          res = a++;  
          // First assum res = 10 only, after increment occur a = 10 + 1 => a = 11
          printf("a is %d and res is %d\n", a, res);  // Now a becomes 11 & res becomes 10

          // post-decrement example:
          // res is assigned 11 only, a is not updated yet
          res = a--;
          //First assum res = 11 only, after decrement occur a = 11 - 1 => a = 10
          printf("a is %d and res is %d\n", a, res); // a becomes 10 now

          // pre-increment example:
          // res is assigned 11 now since
          // a is updated here itself
          res = ++a;
          //First assum res = 11 only, after increment occur a = 1 + 10 => a = 11

          // a and res have same values = 11
          printf("a is %d and res is %d\n", a, res);

          // pre-decrement example:
          // res is assigned 10 only since a is updated here
          // itself
          res = --a;
          //First assum res = 10 only, after decrement occur a = 1 - 11 => a = 10

          // a and res have same values = 10
          printf("a is %d and res is %d\n", a, res);

          return 0;
      }
