# Python for Beginner
If you are curious about Python programming and want to learn more about it, sure, you can browse this page!
This README will provide you a clear grasp of some important fundamental in Python, making your learning experience more enjoyable and straightforward.

Happy growing!

## About Python Variables
A variable is a placeholder for data that Python can remember later in the coding process when an action is needed. Technically speaking, the variable serves as an address for where the data is kept in memory. A Python variable can be allocated a value of one type, then reassigned a value of another type.

To make a value in a variable, the `=` operator can be used between the variable name and the value to be stored.
For Example:
- x = "blueberry"
- x = 5

## Introducing to Python Data Types
### Python Numbers
1. Integer
Integers do not have decimals and can be any length as long as the necessary memory is available.
2. Float
Floating point numbers are those that contain decimals.
3. Complex
Complex numbers (as in mathematics) take the form `a + bj`, where:
- `a` represents the real part
- `b` represents the imaginary part

### Python Boolean
Boolean data type has two values: `True` and `False`. These two values are also Python's reserved keywords.

### Python String
A string is a group of characters separated by `''` or `" "`

### Python List
A list is a collection of objects. The entries in a list are enclosed in brackets `[ ]` and separated by commas.

### Python Tuple
Tuples are equivalent to lists. The difference is that **tuples are immutable**, but **lists are not**. This means that once produced, tuples cannot be changed. The items of a tuple are enclosed in parenthesis `( )` and separated by commas.

### Python Dictionary
A dictionary is a collection of key-value pairs. It can be viewed as a mapping structure in which keys are assigned to values.

### Python Set
A set is an unordered collection of unique, immutable things. The items in a set **cannot be replicated or modified** once they have been formed. We can also execute mathematical operations on sets, such as union and intersection. The items in a set are enclosed in braces `{ }` and separated by commas.

### Others on Python
- `int()`: convert a value into an integer
-  `float()`: convert a value into a float
-  `str()`: convert a value into a string
-  `bool()`: convert a value into a boolean
-  `type()`: determine the data type of a variable or a value
-  `isintance()`: check whether an object belongs to a specific class.

## About Python Input
This set of code requests user input and stores it in the message variable. Inputs are automatically saved as strings. As a result, always convert to integers before performing any mathematical operations.

## About Python Operators
Symbols that represent specific actions or operations on values and variables in a program, such as addition, multiplication, or comparison.
# 1. Arithmetic Operators
Arithmetic operators accept numerical values as operands and return just one numerical value. Here are the common list:
- `+`: adds operands
- `-`: subtracts the right operand from the left operand
- `*`: multiplies both operands
- `/`: quotient of dividing the left operand by the right operand
- `//`: quotient of dividing the left operand by the right
- `%`: the remainder after dividing the left operand by the right operand
- `**`: left operand increased to the power of the right operand

**#NOTES**
The difference `/` and `//`:
- when `/` operates, it returns the quotient as is.
- when `//` operates, it returns the quotient by truncating the fractional part and returning only the integer portion.
# 2. Relational Operators
Relational operators determine the relationship between two operands. It returns True if the relationship is valid and False if it is not. Here are the common list:
- `==`: equal to
- `!=`: not equal to
- `>`: greater than
- `<`: less than
- `>=`: greater than or equal to
- `<=`: less than or equal to

**#NOTES**
The difference `=` and `==`:
- when `=` operates, it returns as an assignment operator
- when `==` operates, it returns an equality operator
# 3. Logical Operators
Here are the common list:
- `and`: if both the operands are True, the condition becomes True
- `or`: if any one or both the operands are True, the condition becomes True
- `not`: it is used to reverse the situation. So, if a condition is True, then it is False (vice versa)
