```python
print("Twinkle, twinkle, little star, \n\tHow I wonder what you are! \n\t\tUp above the world so high, \n\t\tLike a diamond in the sky. \nTwinkle, twinkle, little star, \n\tHow I wonder what you are!")

```

    Twinkle, twinkle, little star, 
    	How I wonder what you are! 
    		Up above the world so high, 
    		Like a diamond in the sky. 
    Twinkle, twinkle, little star, 
    	How I wonder what you are!
    


```python
import sys
print(sys.version)
```

    3.7.4 (default, Aug  9 2019, 18:34:13) [MSC v.1915 64 bit (AMD64)]
    


```python
from datetime import datetime
# datetime object containing current date and time
now = datetime.now()
 
print("now =", now)
# dd/mm/YY H:M:S
dt_string = now.strftime("%d/%m/%Y %H:%M:%S")
print("date and time =", dt_string)	
```

    now = 2019-11-14 20:38:41.396755
    date and time = 14/11/2019 20:38:41
    


```python
PI = 3.14
r = float(input('Enter the radius of the circle :'))
area = PI * r * r
print("Area of the circle is : %.2f" %area)
```

    Enter the radius of the circle :25
    Area of the circle is : 1962.50
    


```python
first_name = input("enter your first name: ")
last_name = input("enter your last name: ")
full_name = last_name + " " + first_name
print(last_name + " " + first_name)
```

    enter your first name: Waqar
    enter your last name: Ahmed
    Ahmed Waqar
    


```python
x = int(input("enter a number :"))
y = int(input("enter another number: "))
print(x+y)
```

    enter a number :786
    enter another number: 789
    1575
    
