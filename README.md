###A python Program which will find all such numbers which are divisible by 7 and are not multipe of 5, between 2000 to 3000.


number=[]
for x in range(2000, 3000):
    if (x%7==0) and (x%5!=0):
        number.append(str(x))
print (','.join(number))
