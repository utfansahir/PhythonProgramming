```python
def add(x, y):
   return x + y
def subtract(x, y):
   return x - y
def multiply(x, y):
   return x * y
def divide(x, y):
   return x / y

print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")

choice = input("Enter choice(1/2/3/4): ")
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
if choice == '1':
   print(num1,"+",num2,"=", add(num1,num2))
elif choice == '2':
   print(num1,"-",num2,"=", subtract(num1,num2))
elif choice == '3':
   print(num1,"*",num2,"=", multiply(num1,num2))
elif choice == '4':
   print(num1,"/",num2,"=", divide(num1,num2))
else:
   print("Invalid input")
```

    Select operation.
    1.Add
    2.Subtract
    3.Multiply
    4.Divide
    Enter choice(1/2/3/4): 1
    Enter first number: 256
    Enter second number: 253
    256.0 + 253.0 = 509.0
    


```python
test_list = [ 1, 6, 3, 5, 3, 4 ]
for i in test_list: 
    if(i == 4) : 
        print ("Element Exists") 
```

    Element Exists
    


```python
key = {0:40, 1:20}  
print(key)  
key.update({2:238})  
print(key)
```

    {0: 40, 1: 20}
    {0: 40, 1: 20, 2: 238}
    


```python
def returnSum(myDict):   
    sum = 0
    for i in myDict: 
        sum = sum + myDict[i] 
    return sum 
dict = {'a': 100, 'b':200, 'c':300} 
print("Sum :", returnSum(dict))
```

    Sum : 600
    


```python
def Repeat(x): 
    _size = len(x) 
    repeated = [] 
    for i in range(_size): 
        k = i + 1
        for j in range(k, _size): 
            if x[i] == x[j] and x[i] not in repeated: 
                repeated.append(x[i]) 
    return repeated  
list1 = [10, 20, 30, 20, 20, 30, 40, 50, -20, 60, 60, -20, -20] 
print (Repeat(list1)) 
```

    [20, 30, -20, 60]
    


```python
d = {1: 10, 2: 20, 3: 30, 4: 40, 5: 50, 6: 60}
def is_key_present(x):
  if x in d:
      print('Key is present in the dictionary')
  else:
      print('Key is not present in the dictionary')
is_key_present(7)
```

    Key is not present in the dictionary
    


```python

```
