```python
class Car():
    def __init__(self,name,model,colour,yearofmanufacturing,chassisnumber):
        self.name = name
        self.model = model
        self.colour = colour
        self.yearofmanufacturing = yearofmanufacturing
        self.chassisnumber = chassisnumber
        
    def average(self,kilo):
        print("{} kilometers per liter".format(kilo))
        
    def tank (self):
        print("yes")
        
    def untouched_engine (self):
        print("yes")
        
    def automatic (self,):
        print("yes")
        
    def remote_starter (self,):
        print("yes")
        
        
car1 = Car('audi','A3','black', '1992', '2345678098')

car1.remote_starter()
```

    yes
    


```python

```
