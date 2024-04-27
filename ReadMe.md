# Learn Python
Python is a general purpose programming language. It is used for different things like automation, data science, machine learning, web development, desktop apps, cli etc. This is a document where i am going to put down everything i learn about python and all. Let's start the journey to the greatness or the echo. Take help from AI along the way!
- Dynamic typing: The code dynamically adds type to a variable by the value. No need to define the type.

## Basics
### Variables and simple data types
- **Variables** are very easy to define in python. `name = "mahi160"` where *name* is the variable.
- Before we start on data types, let's learn some keywords. 
  - Primitive: Represent single values and are stored directly in memory.
  - Non-primitive data types: Represent collections of values and store *references* to the memory location of the actual data.
  - Immutable: Can't be modified once defined.
- Here are data types in python
```python
a_int = 5 # defines whole numbers, primitive, immutable
a_float = 3.14 # defines fraction number, primitive, immutable
a_complex = 3+2j # defines complex numbers, primitive, immutable
a_list = [1, "sifat"] # elements can be of different type
a_dictionary = {"name": "sifat", age: 120} # key value pairs
a_tuple = (10, "hello") # can have different type, immutable
a_set = {1,2,"three"} # no duplicate are allowed
```
That's all here. Now homework!
- If numbers are immutable, how we are able to resign them?
- How do python manage memory?