# Ascendeum_round_2_python_pattern_question
** This piece of code in python helps to print diamond pattern based on the user input as how many character pattern is needed to be printed.
**We have made use of nested for loop to achieve this shape.

Code->

n=int(input('Enter the input value'))

for i in range(1,n+1):
  print(" "*(n-i),end="")
  for j in range(i):
    print(chr(65+j),end=" ")
  print()

for i in range(n-1,0,-1):
  print(" "*(n-i),end="")
  for j in range(i):
    print(chr(65+j),end=" ")
  print()

Pattern:

Enter the input value6
     A 
    A B 
   A B C 
  A B C D 
 A B C D E 
A B C D E F 
 A B C D E 
  A B C D 
   A B C 
    A B 
     A 
