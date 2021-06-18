
**Task-2  AP19110010078**


```python
#Write a program to check whether the user is eligibe to vote or not 
x=int(input("Enter your age:"))
if (x>=18):
    print("You are eligible to vote")
else:
    print("You are not eligible to vote")
    
```

    Enter your age:19
    You are eligible to vote
    


```python
#to check whether the given number is positive or not
x = int(input("Enter your number:"))
if(x>0):
    print("The number is positive:",x)
elif(x<0):
    print("The number is negative:",x)
else:
    print("The number is zero")
```

    Enter your number:25
    The number is positive: 25
    


```python
#To check whether the given number is odd or even, and if it's even checck will it be divided by 4 or not
x= int(input("Enter your number:"))
if (x%2==0 and x%4==0):
    print("The number is even and divisible by 4",x)
elif(x%2==0 and x%4!=0):
    print("The number is even but not divisible by 4")
else:
    print("The number is odd")
```

    Enter your number:14
    The number is even but not divisible by 4
    


```python
#program to print the student grades based on the percentages
x= int(input("Enter your percentage"))
if(x>=60):
    print("The student passed in distinction",x,"%")
elif(x>=35 and x<60):
    print("The student is just pass",x,"%")
else:
    print("The student failed")
```

    Enter your percentage87
    The student passed in distinction 87 %
    


```python
#To check the given year is leap year or not
x=int(input("Enter the year:"))
if(x%4==0 and x%100!=0):
    print("The year is leap year",x)
elif(x%100==0):
    print("The year is not a leap year",x)
elif(x%400==0):
    print("The year is leap year",x)
else:
    print("The year is not a leap year")
```

    Enter the year:1985
    The year is not a leap year
    


```python

```
