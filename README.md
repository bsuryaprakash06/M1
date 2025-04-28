
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read a symbol from the user and to display the same symbol.


## ALGORITHM:
1.Declare a character variable z.

2.Input a character from the user into z.

3.Output the character stored in z.

4.End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    char z;
    scanf("%c",&z);
    printf("%c",z);
    return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/365cf937-0c56-46a7-a238-6f5776346604)



## RESULT:
Thus, the C program to read a symbol from the user and display the same symbol was successfully written, compiled, and executed.

# EX-02- Conditional-Statements
## AIM:
Write a C program to check whether the given number is  even number and if  it is even  check  whether the given number it is less than or equal to  10 or not using nested if.
# ALGORITHM:
1.Declare an integer variable z.

2.Input an integer from the user into z.

3.Check if z is divisible by 2 (even number).

4.If even, print "The number is even" and check if it is less than or equal to 10; if yes, print that.

5.If not even, print "The number is NOT an even number."

# PROGRAM:
```
#include <stdio.h>
int main()
{
    int z;
    scanf("%d",&z);
    if(z%2==0)
    {
        printf("The number is even\n");
        if (z<=10)
        {
            printf("The number is less than  or equal to 10");
        }
    }
    else
    {
        printf("The number is NOT an even number");
    }
}
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/b295ba6a-bd54-492b-805f-db6873d3534e)



# RESULT:
Thus, the program to read a value and check whether it is an even number, and if it is even, to further check whether it is less than or equal to 10 using nested if, has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to find the difference between simple interest & compound interest.


## ALGORITHM:
1.Declare variables p, n, r, SI, A, ci, and diff as float.

2.Input principal (p), number of years (n), and rate of interest (r).

3.Calculate and print simple interest (SI) and amount (A) using formulas.

4.Calculate and print the difference between compound interest and simple interest.

## PROGRAM:
```
#include <stdio.h>
#include <math.h>
int main()
{
    float p,n,r,SI,A,ci,diff;
    scanf("%f %f %f",&p,&n,&r);
    SI=(p*n*r)/100;
    printf("Simple Interest = %.2f",SI);
    A=p*(pow(1+r/100,n));
    printf("\nAmount = %.2f",A);
    ci = A - p;
    diff=ci-SI;
    printf("\nAmount Difference between simple interest & Compound Interest = %.2f",diff);
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/1280136c-6bc3-494b-93ed-051caa1c2189)



## RESULT:
Thus, the program to find the difference between simple interest and compound interest was successfully written, compiled, and executed.



# EX-04- Using Conditional Statements

## AIM:
Write a C program to find the absolute value of a number entered by the user through the keyboard without using predefined function using simple if statement?

## ALGORITHM:
1.Declare an integer variable a.

2.Input an integer from the user into a.

3.Check if a is less than 0.

4.If a is less than 0, print -a as the absolute value.

5.Otherwise, print a as the absolute value.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a<0){
        printf("Absolute value = %d",-a);
    }
    else{
        printf("Absolute value = %d",a);
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/fd23a546-303e-450d-a3b7-51eecf87c46a)


## RESULT:
Thus, the program to find the absolute value of a number entered by the user without using any predefined function, using a simple if statement, was successfully written, compiled, and executed.


# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
Write a C program to calculate total, average and percentage of six subjects.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float s1,s2,s3,s4,s5,s6;
    float tot,avg,per;
    scanf("%f %f %f %f %f %f",&s1,&s2,&s3,&s4,&s5,&s6);
    tot=s1+s2+s3+s4+s5+s6;
    avg=tot/6;
    per=avg;
    printf("Total marks = %.2f\n",tot);
    printf("Average marks = %.2f\n",avg);
    printf("Percentage = %.2f\n",per);
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/e17599d9-0325-4f40-9ce2-331f793731d9)



## RESULT:
Thus, the program to calculate the total, average, and percentage of six subjects was successfully written, compiled, and executed.


