Class
=======
```python
class Person:

    # class variable
    id = 'test'

    # constructor
    def __init__(self, name):
        # instance variable
        self.name = name

    def say_hello(self):
        print('Hello', self.name)

p = Person('test')

# Accessing class variable using class name
Person.id
# Accessing instance variable
p.name
```
