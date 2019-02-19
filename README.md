# Magic Methods in Python 3: What Makes Python Python

This material was presented to the Omaha Python User Group on 2/28/2019

## Abstract
Have you ever wondered how Python works? In this presentation we will uncover the "magic" behind the scenes in Python.  Join us as we discover how: 

- Objects are created and destroyed;
- To give meaningful descriptions to your objects;
- Common mathematical symbols are implemented in Python;
- Python evaluates equity and inequity and; 
- **You, the user, can alter Python's builtin behavior.**

After this presentation you will leave with three key pieces of information:

1) A greater understanding of how Python works;
2) When and how to override Python's magic methods and;
3) Additional resources to learn more about magic methods.

## Viewing This Presentation Locally
- Clone this repository.
- Create a virtual environment and activate it:
```
python -m venv /path/to/ENV
source ENV/bin/activate
```
- Install the the requitred libraries in your virtual environment:
```
pip install -r requirements.txt
```
To open as a Jubyter Notebook:
```
jupyter notebook
```
To display as a slideshow:

```
jupyter nbconvert 'Python 3 Magic Methods.ipynb' --to slides --post serve
```

## Good Resources To Learn More

Official Documentation: https://docs.python.org/3/reference/datamodel.html#special-method-names

- https://rszalski.github.io/magicmethods/

- https://www.python-course.eu/python3_magic_methods.php

- https://dbader.org/blog/python-dunder-methods

- https://micropyramid.com/blog/python-special-class-methods-or-magic-methods/

- https://www.geeksforgeeks.org/dunder-magic-methods-python/

- https://opensource.com/article/18/4/elegant-solutions-everyday-python-problems

- http://farmdev.com/src/secrets/magicmethod/index.html

- https://codesachin.wordpress.com/2016/06/09/the-magic-behind-attribute-access-in-python/