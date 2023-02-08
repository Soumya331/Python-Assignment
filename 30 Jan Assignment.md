Ans1)
```python
n= int(input("Enter your marks:"))
if n>90:
    print("A")
elif n > 80 and n <= 90:
    print("B")
elif n >=60 and n <=80:
    print("C")
elif n<60:
    print("D")
```

    Enter your marks: 8


    D

Ans2)

```python
n = int(input("Enter cost price"))
if n>100000:
    print("Road Tax will be", n*0.15)
elif n > 50000 and n <= 100000:
    print("Road tax will be",n*0.1)
elif n <= 50000:
    print("Road tax will be",n*0.05)
```

    Enter cost price 67


    Road tax will be 3.35

Ans3)

```python

city = str(input("Enter the name of city"))
if city=="Delhi":
    print("Red Fort")
elif city=="Agra":
    print("Taj Mahal")
elif city=="Jaipur":
    print("Jai Mahal")
else:
    print("I don't know")
```

    Enter the name of city Agra


    Taj Mahal

Ans4)

```python
number = int(input("Enter number"))
ans = 0
while number>10:
    number=number/3
    ans=ans+1
print(ans)
    
```

    Enter number 45


    2


Ans5)The purpose of loops is to repeat the same, or similar, code a number of times. This number of times could be specified to a certain number, or the number of times could be dictated by a certain condition being met.
Example:  while loop
i = 1
while i < 6:
  print(i)
  i += 1
  
for loop
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)

Ans6)
```python
n = int(input('Enter number of rows : '))
 
i = 1
while i <= n :
    j = 1
    while j <= i:
        print("*", end = " ")
        j += 1
    print()
    i += 1
```

    Enter number of rows :  6


    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    * * * * * * 



```python
n = int(input('Enter number of rows : '))
 
i = 1
while i <= n :
    j = n
    while j >= i:
        print("*", end = " ")
        j -= 1
    print()
    i += 1
```

    Enter number of rows :  6


    * * * * * * 
    * * * * * 
    * * * * 
    * * * 
    * * 
    * 



```python
rows = 5
i = 1
while i <= rows:
    j = i
    while j < rows:
        # display space
        print(' ', end=' ')
        j += 1
    k = 1
    while k <= i:
        print('*', end=' ')
        k += 1
    print()
    i += 1

i = rows
while i >= 1:
    j = i
    while j <= rows:
        print(' ', end=' ')
        j += 1
    k = 1
    while k < i:
        print('*', end=' ')
        k += 1
    print('')
    i -= 1
```

            * 
          * * 
        * * * 
      * * * * 
    * * * * * 
      * * * * 
        * * * 
          * * 
            * 
              

Ans7)

```python
n=10
while n>=0:
    print(n)
    n=n-1
```

    10
    9
    8
    7
    6
    5
    4
    3
    2
    1
    0

Ans8)

```python
n=10
while n>=0:
    print(n)
    n=n-1
```

    10
    9
    8
    7
    6
    5
    4
    3
    2
    1
    0



```python

```

