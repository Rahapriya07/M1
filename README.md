
# EX-01-Datatypes-Operators
## Name:Raha Priya Dharshini M
## Reg no.:212224240124
## AIM:
Write a C program to find the ASCII value of a given character.

## ALGORITHM:
1.Declare a variable to store the character (char ch)

2.Prompt the user to enter a character

3.Read the character from input

4.Convert the character to its ASCII value using typecasting or implicit conversion

5.Display the ASCII value using printf

## PROGRAM:
```#include <stdio.h>

int main() {

    char ch;
    
    scanf("%c", &ch);

    printf("ASCII value of %c is %d\n", ch, ch);

    return 0;
}
```

## OUTPUT:
![Screenshot 2025-05-22 230609](https://github.com/user-attachments/assets/5f27c763-0335-4ec0-9bc7-c08e1896c3b2)



## RESULT:
Thus the program to find the ASCII value of a given character has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a program in C to read any Month Number in integer and display the number of days for this month.

# ALGORITHM:
1.Declare an integer variable month.

2.Prompt the user to enter the month number (1 to 12).

3.Read the input using scanf.

4.Use a switch statement to match the month number.

5.For months with 31 days: display 31.

6.For months with 30 days: display 30.

7.For February (2): display 28 or 29 days.

8.If the month number is not between 1 and 12, display an invalid input message.

# PROGRAM:
```#include <stdio.h>

int main() {
    int month;

    
    scanf("%d", &month);

    // Checking the number of days in the month
    if (month == 1 || month == 3 || month == 5 || month == 7 || 
        month == 8 || month == 10 || month == 12) {
        printf("Month have 31 days.\n");
    } 
    else if (month == 4 || month == 6 || month == 9 || month == 11) 
    {
        printf("Month have 30 days.\n");
    } 
    else if (month == 2) 
    {
        printf("Month has 28 or 29 days (leap year dependent).\n");
    } 
    else 
    {
        printf("Invalid month number! Please enter a number between 1 and 12.\n");
    }

    return 0;
}
```


# OUTPUT:
![Screenshot 2025-05-22 231609](https://github.com/user-attachments/assets/6d752a40-8d83-449f-8043-4838296de451)


# RESULT:
Thus the program to read any month and get the number of days has been executed successfully.
 
 

# EX-03- Operators-Expressions
## AIM:
Write a C program to check if the given number (For ex: 50) is even number or not using conditional operators.

## ALGORITHM:
1.Declare an integer variable num.

2.Prompt the user to enter a number.

3.Read the number using scanf.

4.Use the conditional operator to check if num % 2 == 0.

5.If true, print "Even number".

6.If false, print "Odd number".

## PROGRAM:
```#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a%2 == 0){
        printf("The number is Even");
        
    }else{
        printf("The number is not Even Number");
    }
    return 0;
}
```

## OUTPUT:
![Screenshot 2025-05-22 232143](https://github.com/user-attachments/assets/ede221dd-f00f-4c25-817d-7981bac305a8)




## RESULT:
Thus the program to check if the given number is even or odd has been executed successfully.

# EX-04- Using Conditional Statements

## AIM:
Write a C program to read a value and print that number is equal to 0 or positive number or negative using an else-if conditional statement.

## ALGORITHM:
1.Declare an integer variable num

2.Read input from the user and store it in num

3.If num is equal to 0

4.Print "The number is zero"

5.Else if num is greater than 0

6.Print "The number is positive"

7.Else Print "The number is negative"

## PROGRAM:
```#include <stdio.h>
int main()  
{
    float a;
    scanf("%f",&a);
    if (a>0)
    printf("number is positive");
    else if(a==0)
    printf("number is 0");
    else
    printf("number is negative");
    return 0;
}
```

## OUTPUT:
![Screenshot 2025-05-22 232347](https://github.com/user-attachments/assets/f466befd-8b80-4011-855d-06d079dfa7eb)


## RESULT:
Thus the program to check whether the input value is equal to 0 or positive or negative using else if statement has been executed successfully


# EX-05- Calculating Total, Average And Percentage of three subjects Using Conditional Statements 
## AIM:
Write a C program to calculate total, average and percentage of three subjects for engineering admission.
## ALGORITHM:
1.Start

2.Declare variables: sub1, sub2, sub3, total, average, percentage

3.Read the marks of three subjects: sub1, sub2, and sub3

4.Calculate total = sub1 + sub2 + sub3

5.Calculate average = total / 3

6.Calculate percentage = (total / maximum_marks) * 100

7.Assuming each subject is out of 100, so total marks = 300

8.Print the total, average, and percentage

9.End

## PROGRAM:
```#include <stdio.h>
int main()
{
    int a,b,c;
    float tm,am,p;

    scanf("%d%d%d",&a,&b,&c);
    tm=a+b+c;
    printf("Total marks = %.2f\n",tm);
    am=tm/3;
    printf("Average marks = %.2f\n",am);
    p=am;
    printf("Percentage = %.2f\n",p);
    return 0;
    
}
```

## OUTPUT:
![Screenshot 2025-05-22 232636](https://github.com/user-attachments/assets/4a0fbed3-ccf7-443c-8913-a921c6695302)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage and average based on predefined grading logic.

