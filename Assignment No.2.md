```python
English = int(input("Enter marks of English: "))
Urdu = int(input("Enter marks of the Urdu: "))
Maths = int(input("Enter marks of the Maths: "))
Chemistry = int(input("Enter marks of the Chemistry: "))
Physics = int(input("Enter marks of the Physics: "))
avg=(English+Urdu+Maths+Chemistry+Physics)/5
if(avg>=90):
    print("Grade: A")
elif avg >= 80 and avg<90 :
    print("Grade: B")
elif avg>= 70 and avg<80 :
    print("Grade: C")
elif avg >= 60 and avg<70 :
    print("Grade: D")
else:
    print("Grade: F")
```

    Enter marks of English: 33
    Enter marks of the Urdu: 45
    Enter marks of the Maths: 54
    Enter marks of the Chemistry: 45
    Enter marks of the Physics: 34
    Grade: F
    


```python
number = int(input("Enter the number :"));
if number == 2 and 4 and 6 and 8 and 10 and 12 and 14 and 16 and 18 and 20 :
    print("Even");
else : 
    print("odd");
```

    Enter the number :15
    odd
    


```python
list_A = [1, 2, 3, "A", "B", "C", 7, 8, 66, 87, 65, 89, 56]
print(len(list_A))
```

    13
    


```python
numbers = [2, 6, 5, 8, 10, 16, -5]
numbersSum = sum(numbers)
print(numbersSum)
```

    42
    


```python
list1 = [10, 20, 50, 70, 100] 
print("Largest element is:", max(list1)) 
```

    Largest element is: 100
    


```python
a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]  
for num in a: 
    if num <= 5: 
       print(num, end = " ") 
```

    1 1 2 3 5 


```python

```
