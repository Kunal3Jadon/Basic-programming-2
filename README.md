# Basic-programming-2
#1..WAP to find hypotenuse from input perpendicular and base
from math import sqrt
a=float(input())
b=float(input())
c=sqrt(a**2+b**2)
print(c)
#2..WAPto calculate distance between two points taking input from the user
x1=int(input())
x2=int(input())
y1=int(input())
y2=int(input())
result=((((x2-x1)**2)+((y2-y1)**2))**0.5)
print(result)
#3..WAP to calculate area of a scalene traingle
a=float(input())
b=float(input())
c=float(input())
s=(a+b+c)/2
area=(s*(s-a)*(s-b)*(s-c))**0.5
print(area)
'''4..WAP to swap values
i)using 3 varaible
ii)without using 3 variable,bitwise and arithmetic operators,if,else,loop
iii)using bitwise
iv)only arithmetic'''

#i)
a=int(input())
b=int(input())
temp=a
a=b
b=temp
print(a,b)
#ii)
a=int(input())
b=int(input())
a,b=b,a
print(a,b)
#iii)
a=int(input())
b=int(input())
a=a^b
b=a^b
a=a^b
print(a,b)
#iv)
a=int(input())
b=int(input())
a=a+b
b=a-b
a=a-b
print(a,b)
