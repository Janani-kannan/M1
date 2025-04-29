
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:

1.	Start the program.
2.	Declare a character variable named character and assign it the value 'A'.
3.	Print the character using printf.
4.	End the program


## PROGRAM:

```
#include <stdio.h>

int main(){
    char character='A';
    
    printf("%c\n",character);
    return 0;
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/a453918c-8176-4484-976c-80adb4234adf)


## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:

1.	Start the program.
2.	Declare an integer variable a.
3.	Read an integer from the user using scanf.
4.	Check if a is equal to 0:
	. If yes, print "Number is ZERO."
  	. If no, print "Number is NOT ZERO."
5.      End the program.



# PROGRAM:
```
#include <stdio.h>
int main(){
    int a;
    scanf("%d",&a);
    if (a==0){
        printf("Number is ZERO.");
    }
    else{
        printf("Number is NOT ZERO.");
    }
}
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/bdc5b680-a9d4-4a7b-80eb-a34b7e6f6c03)

# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Start the program.
2.	Declare two integer variables a and b.
3.	Read two integers from the user using scanf.
4.	Display the numbers before swapping.
5.	Swap the values of a and b using arithmetic operations:
	. a = a + b
  	. b = a - b
  	. a = a - b
6.     Display the numbers after swapping.

End the program.

## PROGRAM:
```
#include <stdio.h>
int main(){
    int a,b;
    scanf("%d%d",&a,&b);
    printf("Numbers before swapping: %d %d\n",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("Numbers after swapping: %d %d\n",a,b);
    return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/9c2ee78c-33bf-4435-85a0-f617bf4bc23a)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:

1.	Start the program.
2.	Declare a character variable ch.
3.	Read a character from the user using scanf.
4.	Check if ch is an alphabet letter:
        . If ch is between 'A'–'Z' or 'a'–'z', continue.
  	. Otherwise, print "Invalid input" and go to step 7.
5.      Check if ch is a vowel (i.e., one of 'A', 'E', 'I', 'O', 'U' or lowercase equivalents):
        . If yes, print "Vowel."
        . Else, print "Consonant."
        . End of decision.
 6.     End the program.

## PROGRAM:

```
#include <stdio.h>
int main(){
 char ch;
 scanf("%c",&ch);
 if((ch>='A' && ch <= 'Z') ||(ch >= 'a'&& ch <= 'z')){
     if (ch== 'A' || ch== 'E' || ch== 'I' || ch == 'O' || ch=='U' ||
     ch== 'a' || ch== 'e' || ch== 'i' || ch== 'o' || ch== 'u')
     printf("Vowel.\n");
     else
     printf("Consonant.\n");
 }else
 printf("Invalid input\n");
 return 0;
    
} 
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/ec1762fb-e056-4562-b010-faf8881d4b60)	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating  total, average and percentage of six subjects.
## AIM:

To write a C program that reads marks of six subjects, calculates the total, average, and percentage, and displays the result.

## ALGORITHM:
1.	Start the program.
2.	Declare six integer variables for marks (s1 to s6).
3.	Declare an integer variable total and float variables average and percentage.
4.	Input marks of six subjects from the user using scanf.
5.	Calculate total: total = s1 + s2 + s3 + s4 + s5 + s6
6.	Calculate average: average = total / 6.0
7.	Calculate percentage: percentage = (total / 600.0) * 100
8.	Display total, average, and percentage using printf.
9.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float eng, phy, chem, math, comp,tamil; 
    float total, average, percentage;
    scanf("%f%f%f%f%f%f", &eng, &phy, &chem, &math, &comp, &tamil);
    total = eng + phy + chem + math + comp + tamil;
    average = total / 6.0;
    percentage = (total / 600.0) * 100;
    printf("Total marks = %.2f\n", total);
    printf("Average marks = %.2f\n", average);
    printf("Percentage = %.2f", percentage);
    return 0;
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/f7d5bc56-95c9-4a57-9900-56b1cdffe177)



## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

