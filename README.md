### 1. python Program which will find all such numbers which are divisible by 7 and are not multipe of 5, between 2000 to 3000.

number=[]
for x in range(2000, 3000):
    if (x%7==0) and (x%5!=0):
        number.append(str(x))
print (','.join(number))



### 2. python program to accept the user's first and last name and then getting them in reverse order with a space between first and last name.

first_name = input("Input your First Name : ")
last_name = input("Input your Last Name : ")
print ("Hello  " + last_name + " " + first_name)


### 3. python program to find the volume of a sphere with diameters is 12 cms.[v=(4/3)*pi*(r**3)]

pi=22/7
r=12/2
v=((4/3)*pi*(r**3))
print("The Volume of a Sphere is :", v)

###
import math
pi=math.pi
r=float(12/2)
v=(float(4/3)*pi*(r**3))
print("The Volume of a Sphere is :", v)
