# EX-16-LEFT-SHIFT-OPERATION
## AIM
Write a C Program to perform bitwise OR operation of two integers. 

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d %d", &a, &b);
    printf("Bitwise-OR result is = %d", a|b);
}

## OUTPUT

<img width="1485" height="852" alt="Screenshot 2025-10-21 161932" src="https://github.com/user-attachments/assets/f36a82eb-95ba-4766-a6ad-97f2ca9b110a" />








## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 
 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to reverse the case of input character using if else

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
#include<stdio.h>
int main()
{
    char n;
    scanf("%c", &n);
    char a=n-32;
    char b=n+32;
    if(n>='a' && n<='z') printf("Reverse case of %c is :  %c", n, a);
    else if(n>='A' && n<='Z') printf("Reverse case of %c is :  %c", n, b);
}


## OUTPUT
<img width="1345" height="875" alt="Screenshot 2025-10-21 162111" src="https://github.com/user-attachments/assets/870691f5-d15c-4925-b79e-5897dc1630c0" />

           
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
To find the length of the string 'CARROT'

OUTPUT:

Length of Str is 6

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
#include<stdio.h>
#include<string.h>
int main()
{
    char str[100];
    scanf("%s", str);
    printf("Length of Str is %lu", strlen(str));
}


## OUTPUT
<img width="1361" height="869" alt="Screenshot 2025-10-21 162242" src="https://github.com/user-attachments/assets/c627d316-4df9-4bbb-8c77-df0f5e9221f2" />





## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C program to convert a string from lowercase to uppercase without using string function using while loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
#include <stdio.h>
int main()
{
    char str[100];
    scanf("%[^\n]", str);
    int i=0;
    while(str[i]!='\0')
    {
        if(str[i]>='a'&& str[i]<='z')
        str[i]-=32;
        i++;
    }
    printf("%s", str);
}

## OUTPUT
<img width="1348" height="866" alt="Screenshot 2025-10-21 162415" src="https://github.com/user-attachments/assets/586a628b-02a2-40bd-9dab-dce3910a1363" />





## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
Write a C Program to perform bitwise AND operation of 6 & 7 integers. 
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
#include <stdio.h>
int main()
{
    int a=6,b=7;
    printf("Bitwise-AND result is = %d", a&b);
    return 0;
}


## OUTPUT
 <img width="1381" height="852" alt="Screenshot 2025-10-21 162517" src="https://github.com/user-attachments/assets/8cd486e7-ff85-4db9-a61b-25451f874f11" />


## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

