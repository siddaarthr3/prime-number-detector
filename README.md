# prime-number-detector
This program finds out if input is prime.

import math

isprime=1
num=input("Enter a number .This program will tell you if the number is prime or not")
numint=int(num)
if numint==2:
    print( num+" is a prime number")
else:   
    for x in (2,math.sqrt(numint)):
        if numint%x==0:
            isprime=0
            break

    if isprime==1:
        print(num +" is a prime number")
    
     

