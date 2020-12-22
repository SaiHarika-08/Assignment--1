# Assignment--1



##1.. A python program which will find the numbers divisible by 7 and are not a multiple os 5, between 2000 to 3000.

number=[]
for x in range(2000, 3000):
    if (x%7==0) and (x%5!=0):
        number.append(str(x))
print (','.join(number))
