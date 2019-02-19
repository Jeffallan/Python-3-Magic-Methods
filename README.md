# Magic Methods in Python 3: What Makes Python Python

This material was presented to the Omaha Python User Group on 2/28/2019

## Abstract

Have you ever wondered how Python works? In this presentation we will uncover the "magic" behind the scenes in Python.  Join us as we discover how: 

- Objects are created and destroyed;
- To give meaningful descriptions to your objects;
- Common mathematical actually work in Python;
- Python evaluates equity and inequity and; 
- **You, the user, can alter Python's builtin behavior.**

After this presentation you will leave with thre key pieces of information:

1) A greater understanding ofhow Python works;
2) When and how to override Python's magic methods and;
3) Additional resources to learn more about magic methods.

## Viewing This Presentation Locally
- Clone this repository.
- Create a virtual environment and activate it:
```
bash
python -m venv /path/to/ENV
source ENV/bin/activate
```
- Install the the requitred libraries in your virtual environment:
```
pip install -r requirements.txt
```

To open as a Jubyter Notebook:
```
bash
jupyter notebook
```

To display as a slideshow:

```
bash
jupyter nbconvert 'Python 3 Magic Methods.ipynb' --to slides --post serve
```