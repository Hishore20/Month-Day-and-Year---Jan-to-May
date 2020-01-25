# Month-Day-and-Year---Jan-to-May


The length of a month varies from 28 to 31 days. In this exercise you will create a program that reads the name of a month from the user as a string. Then your program should display the number of days in that month.

Display 28 or 29 days for February so that leap years are addressed.

The program should get input from Jan to Apr.

If the input is from may to other months then display error messages as "Invalid"

Note:
Use only if and elif
Logic Test Case 1

Input (stdin)
Jan

Expected Output

31
Logic Test Case 2

Input (stdin)
Feb

Expected Output

28 or 29
Mandatory Test Cases

Test Case 1
if
Test Case 2
elif


a=input()
if (a=='Jan' or a=='Mar' or a=='May'):
    print('31')
elif (a=='Feb'):
    print('28 or 29')
elif (a=='Apr'):
    print('30')
	
