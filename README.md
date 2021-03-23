# FRe324-assignment-python-programming-3
1. Write a Python Program to Check if a Number is Positive, Negative or Zero?



code

x = int(input("Enter a number: ")) 

if x > 0:

   print("Positive number")
   
elif x == 0:

   print("Zero")

else:

   print("Negative number")
   
   
   output
   
   
Enter a number: 10

Positive number



2. Write a Python Program to Check if a Number is Odd or Even?
 
 code

x= int(input(" enetr the no."))

if x%2 == 0:

  print("The no. is EVEN")
  
else:

  print("The no. is ODD")
  
  output
  
 enetr the no.20
 
The no. is EVEN

3.Write a Python Program to Check Leap Year?

code


x=int(input("the year to be checked"))

if( x%4 == 0 & x%100 == 0):

  print("the year is leap year ")
  
elif(x%4==0):

   print("the year is lear year")

else:

   print("this is not leap year")
   
   
   output


the year to be checked2020

the year is leap year

4. Write a Python Program to Check Prime Number?
5. 

x = int(input("Enter a number: "))  
 
 
if x > 1:  

   for i in range(2,x):
   
       if (x % i) == 0:
       
           print(x,"is not a prime number")
           
           break
           
       
   else:  
   
       print(x,"is a prime number")
      
else: 

   print(x,"is not a prime number")
   
   
   output
   
Enter a number: 10

10 is not a prime number

5. Write a Python Program to Print all Prime Numbers in an Interval of 1-10000?

code



for x in range(0, 10001):

    if x>1:
    
       for i in range(2, x):
       
           if (x % i) == 0: break
           
       else: print(x)
       
output       

2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
53
59
61
67
71
73
79
83
89
97
101
.......9973
