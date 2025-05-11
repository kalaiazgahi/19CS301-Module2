# 19CS301-Module2
Exp.No:2(a)	ITERATIVE STATEMENTS- PRINTING N NATURAL NUMBERS
### AIM
To write a Python program to find the sum of the series:
1 + X + X³ + X⁵ + ... + Xᴺ (where only odd powers of X including 1 are considered), based on the user input values for X and N.

### ALGORITHM

Step 1: Begin the program.

Step 2: Take input values for X and N from the user.

Step 3: Initialize a variable sum to 0.

Step 4: Use a for loop to iterate through powers from 1 to N (inclusive).
   
Step 5: Also include the initial term 1 in the sum.

Step 6: Display the result.

Step 7: Terminate the program.

### PROGRAM
```
n=int(input())
x=int(input())
sum=0
i=1
while(i<=n):
    sum+=pow(x,i)
    i+=2
print("The sum of the series = ",sum)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/09be28cd-827a-4b08-92d5-bfdc536d9492)


 
### RESULT

Thus, the Python program to find the sum of the series 1 + X + X³ + X⁵ + ... + Xᴺ has been implemented and executed successfully.



Exp.No:2(b)	FUNCTIONS-PERFECT NUMBER

### AIM
To write a Python Program to check if a number is a Perfect number using the concept of functions.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read the number n from the user using input().

Step 3:	 Convert the input to an integer.

Step 4:	 Define the Function perfectNumber(n) with below steps.

Step 5:	 Initialize a variable factor_sum to 0

Step 6:	Iterate through all numbers from 1 to n//2 (as divisors of a number can't be greater than half of it).

Step 7:	If a number i divides n perfectly (i.e., n % i == 0), add i to factor_sum.

Step 8:	If factor_sum is equal to n, then print the number is a perfect number.Otherwise, print it's not a perfect number.

Step 9:	 Terminate the program.
### PROGRAM
```def perfectnumber(n):
    factor_sum=0
    for i in range(1,n//2+1):
        if(n%i==0):
            factor_sum+=i
    if(n==factor_sum):
        print("The number is a Perfect number!")	
    else:
        print("The number is not a Perfect number!")
num=int(input())
perfectnumber(num)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/cc9562f9-e9f5-4989-82fc-6fcea0ec493f)

### RESULT
Thus the python program to check if a number is a perfect number or not has been implemented and executed successfully.

Exp.No:2(c)	BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS- RELATING TWO NUMBERS

### AIM
To write a Python program using a lambda function to check the relation between two numbers — whether one is greater, equal, or lesser than the other.
### ALGORITHM

Step 1: Begin the program.

Step 2: Use eval() to get two numbers (num1 and num2) as input from the user.

Step 3: Define a lambda function res that takes two arguments x and y.

Step 4: The lambda function compares the numbers and prints the relationship:
  
Step 5: Call the lambda function by passing num1 and num2 as arguments.

Step 6: Terminate the program.


### PROGRAM
```num1=eval(input())
f=lambda a,b:print(a+b)
a=int(input())
b=int(input())
f(a,b)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/df39b424-4290-4d0a-8500-95926e94d627)


### RESULT
Thus, the Python program using a lambda function to compare two numbers has been implemented and executed successfully.




Exp.No:2(d)	LOOPING PATTERNS- PRINTING PATTERN

### AIM
To write a python program to print the triangular star pattern.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Read the integer n from the user using input(). This will determine the number of rows in the pattern.

Step 3:	 Initialize a variable i = 0. This will be used to control the number of spaces before the stars.

Step 4:	 Loop through rows from 0 to n-1 (this will iterate n times to print the required rows).

Step 5:	  For each row, calculate the number of spaces before the stars. 

Step 6:	 The formula for the number of spaces is ((n - rows - 1) * 2) + i. 

Step 7:	 Print the spaces (" ") using the print(" ", end="") statement. 

Step 8:	 Increment i by 1 after each row.

Step 9:	 For each row, print the stars. The number of stars for each row is equal to rows + 1. Print the stars with print("*", end=" ") to separate them with two spaces.

Step 10:	 After printing each row's stars, print a newline to move to the next row using print("").

Step 11:	 Terminate the program.
### PROGRAM
```n=int(input())
i=0
for rows in range(0,n):
    for cols in range(((n-rows-1)*2)+i):
        print(" ",end="")
    i+=1
    for star in range(rows+1):
        print("*",end="  ")
    print("")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/97a7d6f9-97f1-44e6-a8b1-2c110a717d1c)


 
### RESULT
Thus the python program to print the triangular start pattern has been implemented and executed successfully.
























Exp.No:2(e)	SEB- COMPUTING POWER

### AIM
To write a python Program to compute the power of the given number using appropriate built -in function .
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Input the base number (base) from the user.

Step 3:	 Input the exponent number (exp) from the user.

Step 4:	 Use the built-in pow() function to compute the  base raised to the power of exp.

Step 5:	 Print the result using the print() function, displaying the power of the given number in a formatted manner.

Step 6:	 Terminate the program.
### PROGRAM
```base=int(input())
exp=int(input())
res=pow(base,exp)
print(f"Power of the given number is: {res}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/f0c61287-b7a6-4c76-908d-396f4104d75b)

 

### RESULT
Thus the python program to compute the power using builtin function has been implemented and executed successfully.





