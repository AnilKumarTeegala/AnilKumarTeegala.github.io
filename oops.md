# Object Oriented Programming in Python
## Contents
1. [Class](#Class)
2. [Object](#Object)
3. [Constructor](#Constructor)
4. [Python Packages and modules using OOPs](#Modules-and-Packages-in-Python')


Python is a multi-paradigm programming language. Meaning, it supports different programming approach.

One of the popular approach to solve a programming problem is by creating objects. This is known as Object-Oriented Programming (OOP).

An object has two characteristics:
- attributes
- behavior

Let's take an example:

If `student` is an object then,

- name, age, color are `attributes`
- singing, Writing, Playing are `behavior`

## Class
Class is a collection of attributes and methods

#### Attributes
Attributes are variables of a class that are shared between all of its instances

Types of Attributes
1. **Instance Attributes**:
They are owned by the specific instances of a class. This means for two different instances the instance attributes are usually different
2. **Class variable or Static Variable**:
Class attributes are attributes which are owned by the class itself. They will be shared by all the instances of the class. Therefore they have the same value for every instance. We define class attributes outside of all the methods, usually they are placed at the top, right below the class header.


#### Methods
Methods are functions defined inside the body of a class. They are used to define the behaviors of an object

syntax:
```python
class student:
  attributes
  methods
```
## Objects
An object is an instance of a class. When class is defined, only the description for the object is defined. Therefore, no memory or storage is allocated.

The example for object of student class can be:
```python
obj = student()
 ```
Here, `obj` is object of class `student`
## Special Methods

### __init__
We use the **__init__()** method to initialize (e.g., specify) an object’s initial attributes by giving them their default value (or state). This method must have at least one argument as well as the self variable, which refers to the object itself (e.g.: student)

**`Note:`** We will never have to call the `__init__()` method; it gets called automatically when we create a new `class` instance.
```python
class student:

    # Initializer / Instance Attributes
    def __init__(self, name, rollnumber):
        self.name = name
        self.rollnumber = rollnumber
```
## Constructor


## Modules and Packages in Python
