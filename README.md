# python_modules
#math() 
import math
pie=math.pi 
print("the value of pi is: ",pie)

from math import pi 
print(pi)

math module with the alias 'm'
import math as m 
result=m.sqrt(25)
print("Square root of 25: ",result)

import math as m 
n=int(input())
r=m.sqrt(n)
print(r) 


#factorial using math() module
from math import*
print(factorial(10))

from math import*
n=int(input())
print(factorial(n))


#random() module 
import random
random_num=random.randint(1,10)
print("Random num: ",random_num)

import random 
k,n=map(int,input().split())
random=random.randint(k,n)
print(random)

# generating password by using  random()
import random
paslen=int(input("enter the length of password:"))
s="abcdefghijklmnopqrstuvwxyz0123456789"
p="".join(random.sample(s,paslen))
print(p)

#system module 
import sys 
print(sys.path)
