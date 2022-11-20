## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

python is used for web development, software development, mathematics, system scripting etc. and it has a simple syntax similar to the English language, so it's easy to learn and code that's why we call it as a general purpose and high-level programming language.

Q2. Why is Python called a dynamically typed language?

We don't need to use data types to declare variable, we can directly assign value to the variable and based on the assign value python is  smart enough to get variable type.

Q3. List some pros and cons of Python programming language?

pros:
python is beginner-friendly bcz it's easy to learn and code
Portable
Exntensive Library
Embeddable
IOT Opportunities
Machine Learning

cons:
Slower than Compiled Languages
Python is not 100% secure
Python’s Memory Consumption and Garbage Collection
Multithreading in Python is not exactly true multithreading

Q4. In what all domains can we use Python?

web application development
AI & Machine Learning 
Data Science
Automation
Desktop GUI

Q5. What are variable and how can we declare them?

Variables are containers for storing data values, it is used to refer to memory location.
We don't need to declare variable explicitly in Python, When we assign any value to the variable, that variable is declared automatically.

Q6. How can we take an input from the user in Python?

with the help of input() function.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

string

Q8. What is type casting?

There may be times when we want to specify a type on to a variable, or we want to convert variable into other type, this is called tye casting.
we can cast or define type of variable with constrauction function of that type Ex. str(), int(), float() ...

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes, we can take more than one input from the user using single input() function.
Basically input() will return user input as a string, means whatever user inputs will be return as a string,
so we can make use of split() method of string to split return string by specifying the seperator,

For Ex. user input multyple value in space seperated manner then all those value will be returned as a single string, which then be splitted into multiple value using split().

Q10. What are keywords?

keywords are the reserve words in any programming language, the word has a special meaning that defines commands and specific parameters for that language.

Q11. Can we use keywords as a variable? Support your answer with reason.

No, we can not use keyword as a variable name. keyword has a special meaning that defines commands and specific parameters for that language.

Q12. What is indentation? What's the use of indentaion in Python?

Indentation refers to the spaces at the beginning of a code line.
Indentation is used to indicate a block of code.

Q13. How can we throw some output in Python?

with the help of print() function.

Q14. What are operators in Python?

The operator can be defined as a symbol which is responsible for a particular operation between two operands.
Python provides a variety of operators, which are as follows.

Arithmetic operators
Comparison operators
Assignment Operators
Logical Operators
Bitwise Operators
Membership Operators
Identity Operators

Q15. What is difference between / and // operators?

'/' is the division operator, the result will be decimal number
'//' is the floor division operator, the result will be nearest whole number

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

print(4*'iNeuron')

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

no = int(input('Enter No: '))
if no%2 == 0 : print('{} is Even No'.format(no)) 
else: print('{} is Odd No'.format(no))

Q18. What are boolean operator?

and, or, not are the boolean operators, they are also called logical operators.

Q19. What will the output of the following?
```
1 or 0 = 1

0 and  = 0

True and False and True = False

1 or 0 or 0 = 1
```

Q20. What are conditional statements in Python?

conditional statements helps in Decision making, Decision making allows us to run a particular block of code for a particular decision.
python supports following conditional statements 'if', 'elif' and 'else'.

Q21. What is use of 'if', 'elif' and 'else' keywords?

'if', 'elif' and 'else' keywords are the conditional statements in the python,
it allows us to run a particular block of code when a perticular condition is mate.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

age = int(input("Enter Your Age: "))
print("I can vote") if age>= 18 else print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for n in numbers:
    if n%2 == 0:
        sum += n

print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

x,y,z = list(map(int,input('Enter 3 nos. in space seperated manner: ' ).split()))
print(x) if x > y and x > z else print(y) if y > z else print(z)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

for x in numbers:
    if x % 5 == 0:
        if x > 500: break
        if x > 150: continue
        else : print(x)