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
