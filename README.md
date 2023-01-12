# NeuralNetworkAssignment1
For question1 we are writing a python program for the following:
– Input the string “Python” as a list of characters from console, delete at least 2 characters, reverse the
resultant string and print it and following is the source code

givenStr = "python";
givenStr = givenStr.replace('h','');
givenStr = givenStr.replace('o','');
print(givenStr[::-1]);
 this following source code will give the output if my  Sample input:
•python
•**Sample output:**
•ntyp

**for question2 we are writing python code for  two numbers from user and perform at least 4 arithmetic operations on them.**

x = 8;
y = 9;
print(x+y);
print(x-y);
print(x*y);
print(x/y);

i am performing basic mathematical operations by assigning random numbers to following variables x and y ,variables can be named either A and B depending on programmer and the sample output of the above program is shown below
**output:**
17
-1
72
0.8888888888888888

**for question3 we are writing python code for  that accepts a sentence and replace each occurrence of ‘python’ with ‘pythons’

**inputStr = "I love playing with python";
print(inputStr.replace('python','pythons'));
**
and the following code gives me output as following

output:
I love playing with pythons

**for question4 we are writing python code by Using the if statement conditions to write a program to print the letter grade based on an input class score. Use
the grading scheme we are using in this class.

here i am using if statement condition to calculate the grade based on input score of class

**score = int(input("Enter your score:"));
if score >= 90 and score <=100:
    print("A");
elif score >= 80 and score <=89:
    print("B");
elif score >= 70 and score <=79:
    print("C");
elif score >= 60 and score <=69:
    print("D");
else:
    print("F");**
    
    
  output:
  for example if i give my input value as 25 then the output is F  because it is not accepting the above condition and i give input as 91 then output is A 
