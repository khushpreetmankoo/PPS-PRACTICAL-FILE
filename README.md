# PPS-PRACTICAL-FILE
# **PROGRAMMING FOR PROBLEM SOLVING ESC-18105** 
## NAME- *Khushpreet Singh*
## UNIVERSITY ROLL NO- *1905352* 
## BRANCH- *INFORMATION TECHNOLOGY* 
## SECTION- *IT(A2)* ![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg) 
## **DEPARTMENT OF INFORMATION TECHNOLOGY** 
# **GURU NANAK DEV ENGINEERING COLLEGE, LUDHIANA** 
__________________________________________________
#**PROGRAM NO:1**
*C program to print "welcome to budding engineers"*

```
  #include<stdio.h>
  int main()
   {
     puts ("welcome to budding engineers");
   }
```
```
     Output
  welcome to budding engineers
```
_________________________________________________
#**PROGRAM NO:2**
*C program to print Hello World three times*
```
   #include<stdio.h> 
   int main() 
   { 	
     int n,i; 	
     printf("Enter a number:"); 	
     scanf("%d",&n); 	
     for(i=1;i<=n;i++) 	
     { 		
        printf("Hello World "); 	
      } 
   	return 0; 
    }
```
```
    Input: 3 
     Output: 
     Hello World 
     Hello World 
     Hello World
```
__________________________________________________
#**Program no:3**
* C program to check no is odd or even*
```
   #include <stdio.h>
   int main()
   {
    int number; 
    printf("Enter an integer: "); 
    scanf("%d", &number); 
    if(number % 2 == 0) 
    printf("%d is even.", number); 
    else 
    printf("%d is odd.", number);
    return 0;
    }
```
```
   Output
   Enter an integer: -7 
   -7 is odd.
```
__________________________________________________
#**Program no : 4**
*C program to check no is positive or negative*
```
     #include <stdio.h> 
     int main()
       { 
       int number;  
        printf("Enter a number \n");
        scanf("%d", &number);
        if (number >= 0) 
        printf("%d is a positive number \n", number); 
        else
        printf("%d is a negative number \n", number);
        return 0;
         }
```
```
       Output
  
       Enter a number 
       -10
       -10 is a negative number  
```
__________________________________________________
#**Program no: 5**
*C program to find prime no*
```
    #include <stdio.h>
    int main()
    { 
     int n, i, flag = 0; 
     printf("Enter a positive integer: "); 
     scanf("%d", &n);
     for(i = 1; i <= n; i++) 
      { 
       if(n%i == 0) 
       { 
           flag++; 
           break; 
       } 
      }
        if (flag == 2) 
        printf("%d is a prime number.", n); 
        else 
        printf("%d is not a prime number.", n); 
       } 
       return 0;
      }
```
```
      Output

    Enter a positive integer: 29
    29 is a prime number.
```
__________________________________________________
#**Program no:6**
*C program to check no is palindrome or not*
```
      #include <stdio.h>

        int main()
          {
            int n, r = 0, t;

             printf("Enter a number\n");
            scanf("%d", &n);

              t = n;

              while (t != 0)
                {
                       r = r * 10;
                       r = r + t%10;
                       t = t/10;
                  }

              if (n == r)
              printf("%d is a palindrome number.\n", n);
             else
             printf("%d isn't a palindrome number.\n", n);

              return 0;
             }
```
```
      Output
      Enter a number 123321
      123321is a palindrome number
```
__________________________________________________
#**Program no : 7**
*C program to print table of a number*
```
       #include <stdio.h>
        int main()
        { 
          int n, i; 
          printf("Enter an integer: "); 
            scanf("%d",&n);
           for(i=1; i<=10; ++i) 
          { 
           printf("%d * %d = %d \n", n, i, n*i);
          } 
          return 0;
         }
```
```
     Output
      Enter an integer: 9 
      9 * 1 = 9
      9 * 2 = 18 
      9 * 3 = 27 
      9 * 4 = 36
      9 * 5 = 45 
      9 * 6 = 54
      9 * 7 = 63
      9 * 8 = 72 
      9 * 9 = 81 
      9 * 10 = 90 
```
__________________________________________________
#**Program no 8**
*C program to print table up to range*
```
     #include <stdio.h>
       int main()
       {
        int n, i, range; 
        printf("Enter an integer: "); 
         scanf("%d",&n); 
        printf("Enter the range: ");
        scanf("%d", &range);
        for(i=1; i <= range; ++i) 
         { 
         printf("%d * %d = %d \n", n, i, n*i);
          }
          return 0;
           }
```
```
       Output

      Enter an integer: 12
      Enter the range: 8 
     12 * 1 = 12 
     12 * 2 = 24 
     12 * 3 = 36 
     12 * 4 = 48 
     12 * 5 = 60 
     12 * 6 = 72 
     12 * 7 = 84
     12 * 8 = 96
```
_________________________________________________
#**Program no 9**
*C program to find prime range*
```
       #include <stdio.h>
        int main()
         {
           int low, high, i, flag;
           printf("Enter two numbers: "); 
          scanf("%d %d", &low, &high);
         printf("Prime numbers between %d and %d      are: ", low, high); 
         while (low < high)
          {
            flag = 0; 
             for(i = 2; i <= low/2; ++i) 
           { 
             if(low % i == 0) 
           {
             flag = 1; break; 
            } }
             if (flag == 0)
           printf("%d ", low);
           ++low; 
            } 
         return 0;}
```
```
      Output
      Enter two numbers :20 50
      Prime numbers between 20 and 50 are: 23 29       31 37 41 43 47
```
______________________________________________
#**Program no :10**
*C program to find factorial of a number*
```
     #include <stdio.h>
     int main()
    { 
     int n, i; 
     unsigned long long factorial = 1;    
     printf("Enter an integer: "); 
     scanf("%d",&n); 
     if (n < 0) printf("Error! Factorial of a negative     number doesn't exist."); 
    else { for(i=1; i<=n; ++i)
   {
    factorial *= i; 
   }
    printf("Factorial of %d = %llu", n, factorial); 
  }   return 0;}
```
```
     Output
     Enter an integer: 3
     Factorial of 3 = 6
```
__________________________________________________
#**Program no : 11**
*C program to reverse a number*
```
     #include <stdio.h>
     int main()
     {
      int n, reversedNumber = 0, remainder; 
      printf("Enter an integer: ");
       scanf("%d", &n); 
     while(n != 0)
    { 
     remainder = n%10;
      reversedNumber = reversedNumber*10 +
         remainder; 
     n /= 10; 
    } 
     printf("Reversed Number = %d",
         reversedNumber);
      return 0;}
```
```
     Output
     Enter an integer 1234
     Reversed Number =4321
```
__________________________________________________
#**Program no: 12**
*C program to convert farenhiet to celcius*
```

   #include<stdio.h>

   int main()

   {

      float celsius, fahrenheit;

      printf("\nEnter temperature in Fahrenheit:");

     scanf("%f",&fahrenheit);

      celsius=(fahrenheit - 32)*5/9;

      printf("\nCelsius = %.3f",celsius); 
 }
```
```
     Output
     Enter temperature in farenhiet: 205
     Celcius = 96.11
```
__________________________________________________
#**Program no :13**
*C program to find factorial by recursion*
```
     #include <stdio.h>
     long int factorial(int n);
     int main()
     {
       int n; 
       printf("Enter a positive integer: ");
       scanf("%d", &n);
       printf("Factorial of %d = %ld", n,
       factorial(n)); 
         return 0;
       }
        long int multiplyNumbers(int n)
      {
         if (n >= 1)
         return n*multiplyNumbers(n-1); 
        else
        return 1;
      }
```
```
      Output
      Enter a positive integer : 3
      Factorial of 3= 6
```
__________________________________________________
#**Program no : 14**
*Program to add two matrices*
```
      #include <stdio.h>
       int main()
          {
          int m, n, c, d, first[10][10], second[10].
          [10], sum[10][10];
          printf("Enter the number of rows and
          columns  of matrix\n");
          scanf("%d%d", &m, &n);
          printf("Enter the elements of first matrix\n");
          for (c = 0; c < m; c++)
           for (d = 0; d < n; d++)
           scanf("%d", &first[c][d]);
          printf("Enter the elements of second matrix
            \n");
          for (c = 0; c < m; c++)
           for (d = 0 ; d < n; d++)
           scanf("%d", &second[c][d]);
            printf("Sum of entered matrices:-\n");
             for (c = 0; c < m; c++)
             {
            for (d = 0 ; d < n; d++)
              {
              sum[c][d] = first[c][d] + second[c][d];
              printf("%d\t", sum[c][d]);
                  }
              printf("\n");
          }
       return 0;
       }
```
__________________________________________________
#**Program no :15**
*C program to multiply two matrices*
```
     #include <stdio.h>
     int main()
      {
       int a[10][10], b[10][10], result[10][10], r1, c1, r2,
         c2, i, j, k; 
      printf("Enter rows and column for first matrix:
      "); 
      scanf("%d %d", &r1, &c1);
      printf("Enter rows and column for second
          matrix: "); 
     scanf("%d %d",&r2, &c2); 
     while (c1 != r2)
     { 
        printf("Error! column of first matrix not equal
         to row of second.\n\n"); 
        printf("Enter rows and column for first matrix: "); 
        scanf("%d %d", &r1, &c1); 
        printf("Enter rows and column for second matrix: "); 
        scanf("%d %d",&r2, &c2); } // Storing elements of first matrix.
        printf("\nEnter elements of matrix 1:\n")
        for(i=0; i<r1; ++i)
          for(j=0; j<c1; ++) 
          { 
     printf("Enter elements a%d%d: ",i+1, j+1);    
     scanf("%d", &a[i][j]); } // Storing elements of second matrix.
     printf("\nEnter elements of matrix 2:\n");
     for(i=0; i<r2; ++i) 
     for(j=0; j<c2; ++j) 
    { 
      printf("Enter elements b%d%d: ",i+1, j+1);
      scanf("%d",&b[i][j]); } // Initializing all elements of result matrix to 0
      for(i=0; i<r1; ++i) 
     for(j=0; j<c2; ++j)
      {
       result[i][j] = 0; } // Multiplying matrices a and b and // storing result in result matrix
    for(i=0; i<r1; ++i) 
    for(j=0; j<c2; ++j)
    for(k=0; k<c1; ++k)
    { 
       result[i][j]+=a[i][k]*b[k][j]; } // Displaying the result 
      printf("\nOutput Matrix:\n");
       for(i=0; i<r1; ++i)
       for(j=0; j<c2; ++j) 
       { 
         printf("%d ", result[i][j]);
         if(j == c2-1) 
          printf("\n\n"); 
         } return 0;}
```
__________________________________________________
#*C program to print fibonacci series*#
```
    #include<stdio.h>
    int fibo(int n);
    int main()
    {
     int c, f, n;
     Printf("Enter the no of terms\n");
     Scanf("%d",&n);
     for(c=0;c<n;c++)
     {
      f=fibo(c);
      printf ("%d",f);
     }
    }
    int fibo(int n)
    {
     if(n==0||n==1)
     return (n);
     else
     return (fibo(n-1)+fibo(n-2));
    }
```
```Output
   Enter the no of terms
   5
   0 1 1 2 3 
```
