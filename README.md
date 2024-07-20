# Python-for-Data-Analysis
Repository to work with Python for Data Analysis including NumPy, Pandas, Matplotlib

Python is a general-purpose, versatile, and powerful programming language. It's a great first language because Python code is concise and easy to read. Whatever you want to do, python can do it. From web development to machine learning to data science.

Its flexibility and accessibility make Python a great fit for this job, enabling the whole team to build web applications, data visualizations, and to improve their workflow with custom utilities.

* Keywords: Python has a set of keywords that are reserved words that cannot be used as variable names, function names, or any other identifiers:

  * False, is, return, None, for, True, def, while, and del, not, elif, if, or, else, import.

  * Python is case-sensitive.
 
Python is an object-oriented programming language, and almost everything in Python is an object.

Objects: The Data Records. A data record with fields; an instance of class

Variables: The reference to Objects. A defined name that references an object.

Functions: A reusable piece of code that performs a specific task.

Classes: A template for creating objects (records)

Attributes: The variables of an Object. A field in a record, defined by its class.

Method: The Functions of an Object. A function defined inside a class that operates on its objects.

Here’s a concise breakdown:

* A class is a template that defines the structure and behaviour of an object.
* An object is an instance of a class, with its own set of attributes (data variables) and methods (functions).
* Objects have properties, which are the values assigned to their attributes.
* Methods are functions that operate on an object’s attributes.
* The self variable is a default parameter in Python methods, which refers to the current object being processed.

Creating objects from a class involves using the class name followed by parentheses, as shown in the example code snippet:
```bash
class Bike:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

bike1 = Bike("Honda", "CBR250R")
```
In this example, bike1 is an object of the Bike class, with attributes brand and model set to "Honda" and "CBR250R", respectively.

Note that classes can have multiple objects, and each object has its own set of attributes and methods. This allows for code reuse and facilitates modeling real-world concepts
