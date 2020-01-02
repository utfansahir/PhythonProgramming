```python
friend = {
    'first_name': 'Ahsan',
    'last_name': 'Habib',
    'age': 28,
    'city': 'Karachi',
    }

print(friend['first_name'])
print(friend['last_name'])
print(friend['age'])
print(friend['city'])

friend["qualification"] = "Phd"
print(friend['qualification'])
```

    Ahsan
    Habib
    28
    Karachi
    Phd
    


```python
del friend['qualification']
print(friend)
```

    {'first_name': 'Ahsan', 'last_name': 'Habib', 'age': 28, 'city': 'Karachi'}
    


```python
cities = {
    'Karachi': { 
              "country":"Pakistan",
              "fact": "the city of lights",
              "approx_population": "14.9 million",
    },
    'Lahore': { 
               "country": "Pakistan",
               "fact": "jinne lahore nahe vehqiya oh jamiya hi nyi",
               "approx_population": "11.13 million",
    },

    'Islamabad': { 
                "city_name": 'islamabad',
                "country":"Pakistan",
                "fact": "islamabad is the capital of the top adventurous place Pakistan",
                "approx_population": "1.015 million",
    },

}
print(cities)
```

    {'Karachi': {'country': 'Pakistan', 'fact': 'the city of lights', 'approx_population': '14.9 million'}, 'Lahore': {'country': 'Pakistan', 'fact': 'jinne lahore nahe vehqiya oh jamiya hi nyi', 'approx_population': '11.13 million'}, 'Islamabad': {'city_name': 'islamabad', 'country': 'Pakistan', 'fact': 'islamabad is the capital of the top adventurous place Pakistan', 'approx_population': '1.015 million'}}
    


```python
print(cities[1])
```

    {'city_name': 'lahore', 'country': 'Pakistan', 'fact': 'jinne lahore nahe vehqiya oh jamiya hi nyi', 'approx_population': '11.13 million'}
    


```python
print(cities[2])
```

    {'city_name': 'islamabad', 'country': 'Pakistan', 'fact': 'islamabad is the capital of the top adventurous place Pakistan', 'approx_population': '1.015 million'}
    


```python
prompt = "\nEnter 'quit' when you are finished."
prompt += "\nPlease enter your age: "


while True:
    age = input(prompt)
    age = int(age)


    if age == 'quit':
        break
    elif age <= 3:
        print("Your ticket is free")
    elif age <= 10:
        print("Your ticket is $10")
    else:
        print("Your ticket is $15")
```


```python
def favorite_book(title):
result=title+the_scariest_book_ever
print(result)
```


```python
import random
target_num, guess_num = random.randint(1, 3), 0
while target_num != guess_num:
    guess_num = int(input('Guess a number between 1 and 30 until you get it right : '))
print('Well guessed!')
```

    Guess a number between 1 and 30 until you get it right : 2
    Guess a number between 1 and 30 until you get it right : 3
    Well guessed!
    


```python

```
