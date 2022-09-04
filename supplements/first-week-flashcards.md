Heading.

---

We can organize our notebook by using headings. # for heading 1, ## for heading 2...etc.

===

`def`

---

We can define functions by using `def` and `return` to get what is returned.

===

`np.array`

---

We use `np.array` to create an array that we can perform math on it.

===

`print ()`

---

The code `print` would print the desired thing for us.

===

`np.linspace`

---

To create ranges of numbers with the given spacing.

===

`numpy`

---

A computational python library used for array creation and provide functionality similar to MATLAB for use for computing purposes

===

`scipy`

---

A scientific library which allows for calculus to be performed on the data. Requires `numpy` to be imported before it can be used.

===

`matplotlib.pyplot`

---

A plotting library which can be used to plot diagrams. Uses the `pyplot` API as it is the most similar to MATLAB. Can allow for data to be presented in a graphical format.

===

Formatted string

---

This can be used to format a string to add in a variable so that it can be changed. For example, `f'The value of x is {x}.'`

===

Function

---

Used to code certain features and is designed for reusability. A function has to be general enough such that it can be used for a wide variety of values.

===


What does the following Python notation do?

    ?<object>

---

Prints information about the given object, such as the object type. This will also print the docstring of a function if it is provided by the developer.

===

Describe the difference between @ vs. * vs. ** for matrix multiplication.

---

@ = dot product

* = matrix multiplication

** = power

===

How do you print the float `x=0`. with the following formatting in python?

    1 character before the decimal
    3 characters after the decimal
---

`print(f”x = {x:1.3f}”)`

===

What do the “precision” and “suppress” arguments do in the numpy function `set_printoptions`?

---

Precision is an integer value that controls how many characters after the decimal should be printed. (i.e. if precision = 2, then 2 decimal places will be printed).

Suppress is a Boolean variable. If `suppress = True`, then, very small numbers (such as 5e-16) will be printed as 0.

===

Suppose we are calling function f, which takes two arguments, a and b.

Will the following code work?

`f (b = 2, a)`

Why or why not?

---

This code will not work because it has a keyword argument before a positional argument. When calling a function, positional arguments must always come before keyword arguments.

`f (a, b=2)`, `f (a=2, b=2)`, and `f (b=2, a=2)` are all valid ways to call function `f`.

===


Writing a function in Python

---

Make sure to use the `return` command to obtain an output.

===

Printing results in Python

---

Make sure to use the command `print(f ‘string {value} string’)` to improve readability of your code.

===

Using the `round()` function

---

Be careful when using this function while doing calculations because you will lose precision. Use it only to print values.

===

Lists and arrays

---

The difference between lists and arrays is that arrays can handle mathematical operations for the purpose of solving engineering problems.

===

Function docstring

---

Add docstrings to your functions to help potential readers (and yourself) better understand the purpose and functionality of your code.

===


Markdown

---

A cell for description in Jupyter notebook. It is meant for people to read. You can double click on it to edit. 

===

`numpy`

---

A library for python. With the code `import numpy as np` (`np` can be replaced with any abbreviation you want), You can import `numpy`. And then with `numpy`, you can create arrays.

===

the code `?name_of_function`    (e.g.: `?print`)

---

With `?name_of_function`, the system will display the arguments that can be put into the function and what the function does.

===

the code `import matplotlib.pyplot as plt`

---

With `import matplotlib.pyplot as plt`, you can plot data in array form. It works like Matlab. The `plt` could be replaced by any abbreviation we like.

===

`math`

---

`math` is a python library. It provides common constants and functions. For example, we want to use the constant pi. We can first `import.math`, and then we could use `math.pi`, which will give us pi (3.14....).

===


Markdown

---

If we type content in the cell box in the type of markdown. The cell box will run and display as normal words instead of run it as codes.

===

`linspace`

---

we can create an array of whatever range we set behind the `linspace` function.

===

plotting

---

When we are plotting. We can set lots of style in the plot. For example, we can set the color of the line, name the x-axis and y-axis...etc

===

`def` and `return`

---

By using `def` we can define a function. After running the code. The code of `return` will display the answer of the function we define.

===

jupyterquiz and jupytercards

---

By running these codes we can create small quiz and flashcards to interact with the users. 

===

1. What is the syntax for tuples, arrays, and lists?

---

`tuple = (a,b,c); array = array([a,b,c]); list = [a,b,c]`

===

2. What is Markdown in Jupyter Notebook?

---

Markdown is a markup language for documenting texts.

===

3. How to create a function? Does function needs a return statement?

---
```python
def function(input):

           statements

           return output
```        

No, a function does not require an explicit return statement.

====

4. Write at least two ways to print a value of pi correct to 5 decimal place?

---

`print('%.5f' % numpy.pi)`  or

`print(round(numpy.pi,5))`

===

5. What happens to defined variables when the IPython Kernel is restarted?

---

Restarting IPython Kernel will reset the variables.

===

`matplotlib`

---

A library or package used for data plotting and visualization in Python. It is usually imported with the command line `import matplotlib.pyplot as plt`, with `pyplot` being a module inside `matplotlib`.

===

Formatted string

---

Lines that have text and elements that are replaced depending on values or words attributed to variables. The syntax is `f"text {value or word to be replaced} text."` For example:

The command lines
```
temperature_value = 75

inside_outside = 'outside'

f"The temperature {inside_outside} is {temperature_value} °F."
```
Returns

    The temperature outside is 75 °F.

===

Headings

---

Used to make logical sections and make them easier to read. The syntax for using headings is #heading1 ##heading2, ###heading3. They must be in Markdown cells and become titles for the sections.

===

Creating functions

---

Parts of the code: defining function name, optional docstring, body (the equation), command to return. Remember: import numpy, use identation. Example:

```
import numpy as np
def f(x):
    "function"
    y = np.exp(-0.5*x)*np.sin(x)
    return y
```
===

`linspace`

---

Creates a list of equally spaced values. In a basic setting, the user sets the initial and final values and the number of values the list will have. Remember to `import numpy`, as `linspace` is a method inside this library. The following example code will create a list of 100 evenly spaced numbers between and including 0 and 1.

```
import numpy as np

x= np.linspace (0, 1, 100) 
```
===


Integer division

---


// is the integer division

For example: 1//3

answer:0

===


Insert a new cell above or below

---


Esc a for above
Esc b for below
===


Increment the value by any number

---

Use += and add the number by which the value should be incremented

`a = 4`

For example: to increment the value by 2

```
a+=2

print(a)
```

    6

===

Find the details of a function

---



Define a function and then add ?

```
def f(x):
    "compute 2*x"
    y = x * 2
    return y
```

`?f`

===


Define a function

---

```
def f(x):
    "compute x/10"
    y = x /10
    return y
```

===

Markdown vs code cells

---

Markdown – cells in jupyter notebooks where you can type text, math, and formulas using latex and html functions
Code – cells where you can code python and import different packages for python

===

Python Functions

---

These give you the ability to reuse code instead of having to repeat lines of code, by calling them to perform common or repeated tasks in your code and having them return the answer/answers

===

Formatted String

---

Can use this type of string to directly input variables and solutions into the string, removing magic numbers and ambiguity

===

LaTeX

---

A typing system that allows users to input mathematical symbols and formulas just from their basic keyboard, allowing for clearer messages and ease-of-access to basic mathematics

===

Jupyter Notebook

---
Online notebooks where users can document their work while running coding languages, without needing to download software. Computations are run on a server on the computer and then displayed.

===

`numpy`

---

Always `import numpy as np` for easy use

===

`matplotlib`

---

Used for plotting graphs in Python , import as plt

===
 

"$" sign

---

Use $ sign to denote something mathematical

===

 

`scipy`

---

Use this to solve differentials equations

===

 

Array

---

 

An array always starts and ends with []

===

`numpy`

---

Library on Python for operations on arrays, called as:

`import numpy as np`

===

`matplotlib`

---

Library on Python for mathematical plots called as:

`import matplotlib.pyplot as plt`

Can be used to format the plots too.

===

function

---

A mathematical expression can usually be defined on python as a function, usually returns at least one value.

Syntax: 

```
def function_name ():
    return expression (arguments)
```                           

===

`scipy`

---

Library on python used for integration, optimization and other such mathematical operations.

      Can be called in this way: `import scipy`

===

Markdown cell

---

Text and equations, and other scientific expressions such as chemical formulas can be represented in LaTeX format within this kind of cells on Jupyter notebook.

===

`numpy`

---

`import numpy as np`

===

`scipy`

---

`import scipy as sp`

===

`matplotlib`

---

used for plotting

===

types of numericals

---

integer, float, array

===

for exponential functions

---

`np.exp()`

===

Libraries on Python

---

We have to import libraries to access their certain functionalities. E.g. `numpy` (arrays)

`import numpy as np`

===

Markdown

---

A lightweight markup language for text that is meant for humans to read. For math expressions use LaTex syntax.

===

Plotting on Python 

---

Use library `matplotlib`

`import matplotlib.pyplot as plt`

===

PDF from Jupyter notebook

---

File->Save and Export Notebook As->Webpdf

===

Function definition with one input

---

```
def function_name(optional_arguments):
    "optional docstring"
    body
    return value
```

Don't forget the return  value line!

===

`numpy`

---

`numpy` is a python library which is used to perform mathematical operations on arrays. 

===

Functions

---

Functions help in reusing the code.

===

`matplotlib.pyplot`

---

It is used in python for plotting

===

Strings

---

Strings are used to work with textual data.

===

    # (symbol)

---

Used to add a comment in python

===

Formatting an array

---

get `np.set_printoptions(precision , suppress=True)`

===

Inserting a new cell

---

use a/b (make sure you are out of the cell selection using Esc)


===

make an array from initial value a to b with spacing of x

---

using `linspace`

===

difference between '/', '//' and '%' operator

---

/ -> gives precise value of division

t on front of card 3// -> gives integral value of division

% -> is a mod operator (gives remainder)

===

Line of code that must be written before referencing a library (NumPy for example)

---

`import numpy as np`

===

How to suppress strings from printing

---

Semicolon after the line of code responsible for printing

===

(1) Purpose of a docstring and (2) how to write one

---

(1) Brief description of the function's purpose (2) Indented line containing string inside quotes

===

Positional arguments vs. keyword argument

---

Positional args must be listed in order, but keyword args must be prefaced by "parameter="

Note that positional args cannot follow a keyword arg.

===

What data types can be multiplied by a float? And does one convert a tuple or list into that type?

---

Array, int, other floats.

===

`np.array()`

Python Libraries (`numpy` & `matplotlib`)

---

These Libraries will help to render the mathematical equations and the `matplotlib` will help render the graphs

===

Functions

---

function is defined in python using the syntax - def Function(), the body (the equation), and ending with return, which returns the value which is called for.

===

Function  & the arguments

---

The arguments must be given while calling the function, this will work only the assigned value of the variables used in function are not defined in the function itself

===

Defining a variable

---

variables can be assigned a value to it globally or inside a function too. But the variables that are assigned inside the function are specific to that function, and if not careful can take value from global variable

===

Formatted Strings 

---

These are used to print a variable, a float, you can also print functions in the formatted strings in between the strings

===

`matplotlib`

---

In order to plot data, matplotlib is used. 
For importing it, we run the code
`import matplotlib.pyplot as plt`

===

Functions

---


Functions are used to recycle code and simplify them

```
def function_name(argument)
    body
    return value
```

===
 

Formatted strings

---

Formatted strings are represented by f'' and the variables in the curly brackets are replaced by values taken from the environment 

===

Markdown

---

Markdown is a lightweight markup language used to modify the text written to make it easier for writing  and reading text.
Text styles, lists, bullets and latex(used for math) are all a part of markdown  

===

Order of the Code

---

The code must be run in its proper order, in order to avoid any errors and ensure optimal running of the code. 

===


`numpy`

---

NumPy is a Python library that works with arrays, in domain of linear algebra, fourier transform, and matrices.

===

Scipy

---
It is a scientific computation library and provides more functions for optimization, stats and signal processing.

===

Matplotlib

---

It is used for data visualization and graphical plotting library for Python.

===

Function

---

It is a block of code which only runs when it is called. You have to input a parameter and it returns the value of the function.

===

Quad

---
It is a function in Scipy which returns the value of an integral and its absolute error.

===

`X@Y`

---

returns the dot product( ) of the arrays

===

Float

---

floating point in python language(a positive or negative whole number with a decimal point)

===

`with np.printoptions(precision=n)`

---

shows the indented codes' results(float) to the n decimal places.

===

what is the following code's problem?

```
def f(x):

      y = 2*x

     print(y)
```

---

you always have to use the 'return' syntax for functions

```
def f(x):

     return 2*x
```

===

Positional argument

Keyword argument

---

arguments that can be called by their position in the function call

arguments that can be called by their names and have a default setting. 

===

LaTeX format

---

-   this fraction $\frac{1}{2}$,
-   square root $\sqrt{3}$
-   sum $\sum_{i=1}^{10} t_i$
-   A chemical formula: H$_2$O or $\mathrm{H_2O}$)
-   An integral $\int_a^b f(x)dx$

===

`return`

---

always put a `return` in a function

===

list, tuple, and array

---

```
a_list = [1, 2, 3]
a_tuple = (1, 2, 3)
an_Array = np.array([1, 2, 3])
```

===

float numbers

---

`{varname:width.decimalsf}`

===

search

---

shift+command+C

===

`numpy`

---

A Python library for arrays. 

The conventional way to import this library is:

`import numpy as np`

===

`matplotlib`

---

A Python library to create plots.

The conventional way to import this library is:

`import matplotlib.pyplot as plt`

Some helpful functions include:

`plt.plot(), plt.xlabel(), plt.ylabel(), plt.legend()`

===

Keyboard shortcuts for inserting new cells

---

Esc a for inserting cell above

Esc b for inserting cell below

===

How to make an array

---

`import numpy as np`

`array = np.array([1, 2, 3, 4, 5])`

===

How to temporarily print array x to three decimal places

---

```
with np.printoptions(precision=3, suppress=True):

       print(x)
```

===

How to make the text 'Hello World :D' scroll from right to left across the screen

---

```
from IPython.display import HTML

HTML('<marquee>Hello World :D</marquee>')
```

===


`numpy.linspace`

---

It is calculated over the interval. The numbers are placed evenly at the interval 

===

`print` 

---

The `print()` function states out the specified message to the screen as an output

===

`quad` 

---

It is used to calculate a defined integral

===

Tuples

---

They are the lists surrounded by parentheses. They cannot be changed after being created

===

`numpy.arrays`

---

They can be created as list. The function is like: `n= np.array([])`
 
===


Value Types In Python

---

Integer, Float, String, Boolean

 
===

Definition of a Variable

---

A symbolic name that is a reference or pointer to an object.

 

===

Definition of Print

---

Specify message to the screen, or other standard output devices.

Keyword: `print`

 

===

Definition of Function

---

A group of related statements that performs a specific task.

Keywords: `def`, `return`

 

===

How to get help on doing Markdown in Jupyter notebook 

---

Go Menu Bar → Help → Markdown Reference

===


Markdown

---

Markdown is a lightweight markup language for text that is meant for humans to read.

 

===

Functions

---

They allow you to reuse code, and make programs more readable.

 

===

Global Variable

---

Variable that are created outside of function.

 

===

Strings

---

Text used to present output of work. Made using ''

 

===

Floats

---

Floats are continuous numbers, often with a decimal.  Floats are approximate.

===

Markdown

---

A cell used to present text and mathematical expressions in LaTeX format.

===

Functions

---

A function takes inputs, process the inputs as desired, and returns an output.

===

Numpy

---

Library for numerical python. Used to generate arrays and to code math operations.

===

```
3*[1,2]; 3*(1,2); 3*np.array([1,2])
```

---

    [1,2,1,2]; (1,2,1,2); [3,6]; 
    
only the array allows elementwise calculation. 

===

`from scipy.integrate import quad`

---

`quad (f, a, b)` calculates the definite integral of function f(x) from a to b.

===


True or False: Multiplying a tuple by 2 doubles each element in the tuple

---

False.

 

===
How do you insert a variable value into a printed string

---

`print(f”…{…}…”)`

 
===

 What is wrong with `x = round(x)`?

---

You lose the original value of x, so any calculations using x going forward are less accurate

 

===

Which variable is a required input in `f(x, a=2)`?

---

`x`

 
===

What is displayed when you print a function that does not have a return value?

---

None

===

Syntax to add labels to a graph

---


          plt.xlabel("x")
          plt.ylabel("y"

===



Linspace

---



Create an evenly spaced sequence in a specified interval.

`numpy.linspace(start,stop,numbers)`

===



Defining Function 

---


```
def functionname(parameters):

 #statement

return expression
```

===


Tuple

---


Sequences just like lists. Created by placing all items inside () separated by commas.

===


Writing fractions in LaTeX

---


`\frac{numerator}{denominator}`

===


What is the code to get the python plotting package 

---
`import matplotlib.pyplot`

===

What is the code if you want to print an array 

---

`np.array([])`

===

What should you do if your graph isn’t smooth enough 

---

Assign more data to the variable 

===

How to adjust the size of axis labels

---

`plt.xlabel (“name”,fontsize=number)`

===

A short cut to run your code 

---

Shift + enter

===

`np.ones (a)`

---

Command to create a 1 dimensional array of 'a' number of "1"s 

 

===

`dtype = np.int64`

---

A command to change the data type of an item to integer. By default, the data type of items in an array is float.  

 
===

`arrayname.ndim`

---

A command which returns the number of dimensions of an array where arrayname is the variable for the array

 
===

`arrayname.shape`

---

Command which returns the number of elements stored in each dimension in the array named arrayname. It returns a tuple of dimensions.

 

===

`arrayname.size`

---

A command which returns the number of total of elements stored in the arrayname.

===


Latex

---

Latex is used to write mathematical format in any programming language. 

===

Strings

---

Strings is a sequence of coding characters that represents the output of what we are working.

===

`matplotlib`

---

Matplotlib is a Library in Python used for plotting graphs of several equations.

===

Function

---

Function is defined to get uniquely identified. We define function as `def fun()`

===

Arguments

---

Using the arguments we can pass the values to a function that is defined.

===

Method for plotting

---

`plt.plot(x_value_array, math_function_1, color&symbol, x_value_array, math_function_2, color&symbol_2, ...)`


===

Method for labeling x-axis

---

`plt.xlabel("type label string here")`


===

Method for labeling y-axis

---

`plt.ylabel("type label string here")`

===

Method for labeling the legend for a plot

---

`plt.legend(["name of function 1", "name of function 2", ... ])`

===

Files from Jupyter Notebooks should be saved as...

---

WebPDF (unless you're a LaTeX wizard and won't make a mistake, in which case regular PDF is fine)

===

Numpy 

---

To perform a wide variety of mathematical operations on arrays

===

Scikit - Learn

---

Most useful and robust library for machine learning in Python

===

PyBaMM

---

 Tool for fast and flexible simulations of battery models

===

Seaborn

---

Drawing attractive and informative statistical graphics

===

Pyomo

---

To formulate optimization problems in Python

