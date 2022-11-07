# python-assignment1
Q1. Why do we call Python as a general purpose and high-level programming language?
ans. Python is extensively used language to perform various big data processing. python is easier to use and quite user friendly and interactive language.
     writing syntax is easy in python and it is a high level language that allow user to interact with system in easier manner.

Q2. Why is Python called a dynamically typed language?
ans. because python itself take care of the memory management. and there is no issue to declare the data type.all these things make python a dynamically typed language.

Q3. List some pros and cons of Python programming language? 
ans. PROS-dynamically typed language
          easier syntax
          Large Community	             
          Flexible and Extensible	     
          Extensive Libraries	             
          Embeddable
     CONS-Slower than compiled languages
          Security
       	  Work Environment
	  High memory consumption	

Q4. In what all domains can we use Python?
ans. data science, automation, A.I., application development, machine learning, console application, desktop GUI and various other domain are there where python is used.

Q5. What are variable and how can we declare them?
ans. Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and the value to be assigned to the variable. Unless and until the variables are declared and initialized, they cannot be used in the program.
     eg. a=5, (here a is the variable in which value 5 is assigned,in python we may declare data type or not.).

Q6. How can we take an input from the user in Python?
ans. syntax: a=input(int())    
     input() function used.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
ans. string.

Q8. What is type casting?
ans. converting one datatype to another datatype is called as type casting.
      hrs=input('enter hrs: ')
      rt=input('rate is:  ')
      p=float(hrs)*float(rt)    # type casting.
      print('Pay:',p) 


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
ans. in normal conditions we cant take more than one because a variable stores only 1 value. but it is possible by using split() method, or by changing variable into a list.

Q10. What are keywords?
ans. Keywords are some predefined and reserved words in python that have special meanings. like print, if else, for while etc.

Q11. Can we use keywords as a variable? Support your answer with reason.
ans. no, at a very basic level, not allowing programmers to use keywords as variable names just makes the code more readable. Technically, it’s helpful to the interpreter/compiler developers, too, because they can pick out the keywords from the rest of the code without having to rely entirely on token sequence.  

Q12. What is indentation? What's the use of indentaion in Python?
ans. indenting in python is creating seperate block of codes which tell the python interpreter to run that block of code 1st. 
     eg: a=5
         if a>=5:
             print("true") # indent allow to enter and run that block of code.

Q13. How can we throw some output in Python?
ans. using print() statement. 
       eg: a=5
         if a>=5:
             print("true")  # here output will be true.

Q14. What are operators in Python?
ans. Python Operators in general are used to perform operations on values and variables. These are standard symbols used for the purpose of logical and arithmetic operations. 
     arithmetic operator(+,-,/,*), logical op(and,or), compaison op(a==b,a!=b,a>b,a<b,a>=b,a<=b), assignment op(a+=b,a-=b,a*=b,a/=b).

Q15. What is difference between / and // operators?
ans. '/' is the division operator. '//' is the floor division operator.

'//' is used to obtain the smallest integer nearest to the quotient obtained by dividing two numbers.
     a = 19
     b = 4
     print(a // b)  #This prints output as 4
     print(a / b)  #This prints output as 4.75        
 Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
ans.str_a="iNeuron"
    str_b=str_a*4
    print(str_b)
    
Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
ans. a=int(input())
     if a%2==0:
         print('even')
     else:
         print('odd')
	 
Q18. What are boolean operator?
ans. The logical operators and, or and not are also referred to as boolean operators. While and as well as or operator needs two operands, which may evaluate to true or false, not operator needs one operand evaluating to true or false.
     Boolean and operator returns true if both operands return true.Boolean or operator returns true if any one operand is true,  The not operator returns true if its operand is a false expression and returns false if it is true.
     
 Q20. What are conditional statements in Python?
ans. Python also has some predefined conditional statements. A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions encountered by the program.
     Python has 3 key Conditional Statements:

     if statement
     if-else statement
     if-elif-else statement

Q21. What is use of 'if', 'elif' and 'else' keywords?
ans. if: to execute any specific condition.
     elif: to execute the other condition of the program which not included in if statement.
     else: rest of the condition included in this block other then if and elif. 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
ans. a=int(input())
     if a>=18:
         print('I can vote')
     else:
         print('I can't vote')
	 
Q23. Write a code that displays the sum of all the even numbers from the given list.
numbers = [12, 75, 150, 180, 145, 525, 50]
ans. numbers = [12, 75, 150, 180, 145, 525, 50]
     sum=0
     for i in numbers:
         if i%2 == 0:
             sum = sum + i
     print(sum)
     
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
ans. a=int(input())
     b=int(input())
     c=int(input())
     if a>b and a>c:
         print('a is largest')
     elif b>a and b>c:
         print('b is largest')
     else:
         print('c is largest')
	 
Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
ans. numbers = [12, 75, 150, 180, 145, 525, 50]
     for i in numbers:
     if i%5==0: 
         if i<=150:
             print(i)
         if i>500:
             break

