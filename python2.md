```python
#for varible in range(start,stop):
#code
for i in range(5):
    print(i)
```

    0
    1
    2
    3
    4
    


```python
for i in range(1,11):
    print(i)
```

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    


```python
total= 0
for i in range(1, 11):
    total += i
    
print(total)
```

    55
    


```python
#while condition
i=1
while i<=5:
    print(i)
    i+=1
```

    1
    2
    3
    4
    5
    


```python
for i in range(1,6):
 if i==3:
   continue
 print(i)


```

    1
    2
    4
    5
    


```python
num=int(input("enter the number:"))
for i in range(1,11):
    print(num,"x",i,"=",num*i)
```

    enter the number: 6
    

    6 x 1 = 6
    6 x 2 = 12
    6 x 3 = 18
    6 x 4 = 24
    6 x 5 = 30
    6 x 6 = 36
    6 x 7 = 42
    6 x 8 = 48
    6 x 9 = 54
    6 x 10 = 60
    


```python
num=int(input("enter the number:"))
fact=1
for i in range(1,num+1):
    fact*=i
print(fact)

```

    enter the number: 5
    

    120
    


```python

```
