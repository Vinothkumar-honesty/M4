# EX-16-LEFT-SHIFT-OPERATION
## NAME : VINOTHKUMAR R
## REG.NO : 212224040361
## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main(){
    int a=44;
    a=a<<3;
    printf("After Left Shift Operation value of a is:%d",a);
}
```
## OUTPUT

![M4 1](https://github.com/user-attachments/assets/ffc2e4c3-f842-4087-9ba1-5aa4283c1cd3)


## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 
 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main()
{
    int a,b;
    printf("Enter the value of A and B: ");
    scanf("%d%d",&a,&b);
    if(a==b)
    {
        printf("X is equal to Y");
    }
    else
    {
        printf("X is NOT equal to Y");
    }
    return 0;
}
```
## OUTPUT

![M4 2](https://github.com/user-attachments/assets/19f0a1d2-55c8-4306-96ca-d7a8cc4aaeb4)
           
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char a[100];
    scanf("%s",a);
    for(int i=0;i<strlen(a);i++)
    {
        a[i]=tolower(a[i]);
    }
    printf("Lower case String is:%s",a);
}
```
## OUTPUT

![M4 3](https://github.com/user-attachments/assets/13baee17-870b-4700-81b4-9f096f397e3f)



## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main()
{
    char a[100];
    int l=0;
    printf("Enter the string to count: ");
    fgets(a,sizeof(a),stdin);
    while(a[l]!='\0')
    {
        l++;
    }
    printf("%d",l-1);
    return 0;
}

```
## OUTPUT

![M4 4](https://github.com/user-attachments/assets/fb508a7d-bd02-418b-8265-db035f5b5240)


## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main()
{
    char a[10];
    char b[10];
    scanf("%s",a);
    scanf("%s",b);
    for(int i=0;i<strlen(a);i++)
    {if (a[i]==b[i])
    {
        printf("strings are same");
        break;
    }else
    {
        printf("strings are not same");
        break;
    }
    }
}
```

## OUTPUT
 
 ![M4 5](https://github.com/user-attachments/assets/f9c8d9c7-c8df-4a07-b3d5-159284beebb9)


## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

