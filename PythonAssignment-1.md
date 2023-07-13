## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
ANS: Pyhton is a interpreted language unlike compiled language like c, java etc. we can run interpreted dynamic language in the given system using another program instead of it's local
processor.

Q2. Why is Python called a dynamically typed language?
ANS: Python is a dynamically typed language because we don't need to declare any variable in python. we can just assign the value to the variable it will automatically act as a variable. So declarative typed means, it doesn't know about the datatype until it will complete the program. it will basically store this value to the memory location whenever we required this value we can simply extract it so datatype is not required there. 

Q3. List some pros and cons of Python programming language?
pros = user-friendly, Large community, Flexible and extensible, extensive libraries
cons = issue with design, slower than compiled language, security, work environment. 


Q4. In what all domains can we use Python?
There are multiple domains like data science, data analyst, data engineer, machine learning engineer, web development, game development etc.

Q5. What are variable and how can we declare them?
varible is the pointer of the memory which is creating space inside the memory and we can use that space to store our value.
as we know that python is the high level language we don't need to declare the variable just we can assign the value it will automatically act as a variable.
exampe: var = 10;

Q6. How can we take an input from the user in Python?
we can use the input() function to take an input from the user
ex: var = input("Enter your number: ")

Q7. What is the default datatype of the value that has been taken as an input using input() function?
And: it's a string.

Q8. What is type casting?
type casting is basically mean to chnage your data type of the variable.
example = 
var = "11"
var2 = int(var)
i can use int(), str(), float() etc to chnage the datatype of the variable that's we called a type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
yes, we can do it. 
usinf split() function - example - var1, var2 = input("enter var1 and var2 value = ").split()

Q10. What are keywords?
keywords are the predefined reserved words in python which we can't use in the python to define any varible, function name or anything. it's basically used in python syntax and program.

Q11. Can we use keywords as a variable? Support your answer with reason.
no, we can't use because it's a reserved word which can use in interpreted python language. and it's a king python syntax so we can provide some meaningful names insted of resrved words.

Q12. What is indentation? What's the use of indentaion in Python?
Identation provides you the code block in python or spaces at the starting that you can easily read and understand the program.

Q13. How can we throw some output in Python?
ANS: To throw the output, we use print() funtion in python programming. example: print("Hello World")

Q14. What are operators in Python?
ANS: Operators define matchmatics calculation mark like +,-,/,*,//,% etc.
example: 
var1 = 10
var2 = 10
var3 = var1 + var2
var3 = var1 - var2
var3 = var1 * var2
var3 = var1 / var2
...
Q15. What is difference between / and // operators?
/ operator = will provide you the division value with decimal format. it will also provide you float value in decimal form. example: print(11/2) = 5.5 
// operator = but here in, it will provide you round off value. example if it will have any float value it will basically provide you round off value = print(11/2) = 5
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Multi_Var = "iNeuron"
print(Multi_Var*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Number_var = input("Enter your number = ")
if Number_var % 2 ==0:
	print("Even Number")
Else:
	Print("odd number")

Q18. What are boolean operator?
we can use AND, OR and NOT operator to defined as boolean operator. 
AND = it will provide you the result when both the condition satisfied
OR = it will provide you the result when any one of the condition satisfied
Not = it will give you opposite result of the condition.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans:
1
0
False
1

Q20. What are conditional statements in Python?
conditional operator basically we can provide the condition expression in between IF or Elif condition. expression is like '==', '>=', '<=', '!='.
example: IF x == 0 AND X >= 1:

Q21. What is use of 'if', 'elif' and 'else' keywords?
IF: if condition will provide you the value when input satisfied the condition, it will give you the result
	ex: if x>5: print("condition satisfied")
Elif: if there are multiple condition and we have to process all them into one program then we can also go with the Elif condition.
	ex: if x>5: print("if condition satisfied")
	    elif x>10: print("elif condition satisfied")
Else: if there will not be any if and elif condition satisfied the code will automatically move to the else part and you will get the else condition value in the output.
	ex: if x>5: print("if condition satisfied")
	    elif x>10: print("elif condition satisfied")
	    else:	print("elif condition satisfied")

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age = input("age of the person = ")
if age >= 18:
	print("I can vote")
else: 
	print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
sum = 0
for x in numbers:
    if x % 2 == 0:
	    sum += x
print(sum)	

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

var_num1 = input("Enter 1st number = ")
var_num2 = input("Enter 2nd number = ")
var_num3 = input("Enter 3rd number = ")

if var_num1>var_num2 and var_num1>var_num3:
    print(var_num1, "is the highest number")
elif var_num2>var_num1 and var_num2>var_num3:
    print(var_num2, "is the highest number")
else:
    print(var_num3, "is the highest number")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Code: 

numbers = [12, 75, 150, 180, 145, 525, 50]
for x in numbers:
    if x % 5 == 0:
        if x > 150:
            continue
        if x > 500:
            sys.exit()
        print(x)
		
			