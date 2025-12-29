```python
nums = [10,20,30]
print(nums[2]) #30

```

    30
    


```python
nums = [10,20,30]
print(nums[0:2])
```

    [10, 20]
    


```python
nums=[20,30,40]
print(nums[0])
print(nums[0:2])
nums.append(50) #append = add item at end
print(nums)
```

    20
    [20, 30]
    [20, 30, 40, 50]
    


```python
nums=[20,30,40]
print(nums[0])
print(nums[0:2])
nums.insert(3,50)#insert an element at a specific index
print(nums)
      
```

    20
    [20, 30]
    [20, 30, 40, 50]
    


```python
nums=[20,30,40]
nums.remove(30) #removes an number
print(nums)
```

    [20, 40]
    


```python
nums=[20,30,40]
nums.pop()
print(nums)
```

    [20, 30]
    


```python
nums=[20,30,40]
nums.extend([50,60,70]) # adss multiple elements
print(nums)
```

    [20, 30, 40, 50, 60, 70]
    


```python

```


```python
nums=[20,30,40]
nums.pop() # removes and returns an element
print(nums)
nums.pop(1)
print(nums)
nums.clear() #clears aall the elements
print(nums)


```

    [20, 30]
    [20]
    []
    


```python
nums=[20,30,40]
nums.remove(20) # removes elements
print(nums)
```

    [30, 40]
    


```python
nums=[70,80,80,60]
print(nums.index(80)) #returns the index position of an element
print(nums.count(80)) #counts how many times a value appears
nums.sort() #sorts the list in ascending order by default
print(nums)
nums.sort(reverse=True) #descending order
print(nums)
nums.reverse() #reverses the element
print(nums)

```

    1
    2
    [60, 70, 80, 80]
    [80, 80, 70, 60]
    [60, 70, 80, 80]
    


```python
#tuples-stores multiple values
t=(20,30,40)
print(t[2])
print(t[1])
```

    40
    30
    


```python
#sets - collection that stores unique elements, doesnt allow duplicates
s={1,2,3,4}
print(s)
s.add(6) #adds an element
print(s)
s.update([5,6,7]) #adds elements
print(s)
s.remove(3) #removes an elements
print(s)
a={1,2,3}
b={1,2,4}
print(a|b) #union
print(a & b) #intersection
print(a-b) #difference

```

    {1, 2, 3, 4}
    {1, 2, 3, 4, 6}
    {1, 2, 3, 4, 5, 6, 7}
    {1, 2, 4, 5, 6, 7}
    {1, 2, 3, 4}
    {1, 2}
    {3}
    


```python
#practice questions
t=(1,2,3,4,5)
print(t[0])#prints 1st element
print(t[4])#prints 2nd element
print(t[1:3])#slicing
print(len(t))#counts number of element
print(t.count(5))#counts how many times an element appears in a tuple
```

    1
    5
    (2, 3)
    5
    1
    


```python
data=100,200,300 #packing
a,b,c=data #unpacking
print(a)
print(b)
print(c)
```

    100
    200
    300
    


```python
#a tuple of student names and check whether "amit" exists in the tuple
students=("sanika","saniya","sonika","riya")

if "amit" in students:
    print("amit is present in the tuple")
else:
    print("amit is not present")
```

    amit is not present
    


```python
s={1,2,3,4,5,6}
print(s)
s.add(10)#adds an element 
print(s)
s.remove(3)
print(s)
s.discard(3)
print(s)
print(len(s))
```

    {1, 2, 3, 4, 5, 6}
    {1, 2, 3, 4, 5, 6, 10}
    {1, 2, 4, 5, 6, 10}
    {1, 2, 4, 5, 6, 10}
    6
    


```python
a={1,2,3}
b={3,4,5}
print(a|b)
print(a&b)
print(a-b)
```

    {1, 2, 3, 4, 5}
    {3}
    {1, 2}
    


```python
a={5}
b={5,}
print(a-b)
```

    set()
    


```python
#dictionary 
student={"name":"sanika",
         "age":18,
         "branch":"BTECH"}
print(student)
print(student["name"])

```

    {'name': 'sanika', 'age': 18, 'branch': 'BTECH'}
    sanika
    


```python
#nested
students={"s1":{"name":"A","marks":90}}
print(students["s1"]["marks"])          
```

    90
    


```python


```
