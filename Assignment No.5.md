```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
n=int(input("Input a number to compute the factiorial : "))
print(factorial(n))
```

    Input a number to compute the factiorial : 4
    24
    


```python
def string_test(s):
    d={"UPPER_CASE":0, "LOWER_CASE":0}
    for c in s:
        if c.isupper():
           d["UPPER_CASE"]+=1
        elif c.islower():
           d["LOWER_CASE"]+=1
        else:
           pass
    print ("Original String : ", s)
    print ("No. of Upper case characters : ", d["UPPER_CASE"])
    print ("No. of Lower case Characters : ", d["LOWER_CASE"])

string_test('The quick Brown Fox')
```

    Original String :  The quick Brown Fox
    No. of Upper case characters :  3
    No. of Lower case Characters :  13
    


```python
# Python program to print Even Numbers in a List 
  
# list of numbers 
list1 = [10, 21, 4, 45, 66, 93] 
num = 0
  
# using while loop         
while(num < len(list1)): 
      
    # checking condition 
    if num % 2 == 0: 
       print(list1[num], end = " ") 
      
    # increment num   
    num += 1
```

    10 4 66 


```python
def isPalindrome(string):
	left_pos = 0
	right_pos = len(string) - 1
	
	while right_pos >= left_pos:
		if not string[left_pos] == string[right_pos]:
			return False
		left_pos += 1
		right_pos -= 1
	return True
print(isPalindrome('madam'))
```

    True
    


```python
def isPalindrome(string):
	left_pos = 0
	right_pos = len(string) - 1
	
	while right_pos >= left_pos:
		if not string[left_pos] == string[right_pos]:
			return False
		left_pos += 1
		right_pos -= 1
	return True
print(isPalindrome('fever'))
```

    False
    


```python
def test_prime(n):
    if (n==1):
        return False
    elif (n==2):
        return True;
    else:
        for x in range(2,n):
            if(n % x==0):
                return False
        return True             
print(test_prime(9))
```

    False
    


```python
def test_prime(n):
    if (n==1):
        return False
    elif (n==2):
        return True;
    else:
        for x in range(2,n):
            if(n % x==0):
                return False
        return True             
print(test_prime(2))
```

    True
    


```python
def customer_shopping(*shopping_list):
    print("\n--------- Shopping List --------")    
    for element in shopping_list:
        print("You bought: ",element)

shopping_list = []

while True:
    items = input("\nEnter the item you bought from market \nIf you leave enter'quit': ")
    if items == 'quit':
        break
    shopping_list.append(items)

customer_shopping(shopping_list)
```

    
    Enter the item you bought from market 
    If you leave enter'quit': Carrot
    
    Enter the item you bought from market 
    If you leave enter'quit': Banana
    
    Enter the item you bought from market 
    If you leave enter'quit': mango
    
    Enter the item you bought from market 
    If you leave enter'quit': quit
    
    --------- Shopping List --------
    You bought:  ['Carrot', 'Banana', 'mango']
    


```python

```
