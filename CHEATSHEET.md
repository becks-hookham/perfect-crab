## Functions

A **function** is like a small machine in your code.

- You give it some input (optional).  
- It does something (a set of instructions).  
- It gives you back an output (optional).  

---

## In simple terms
👉 A function is a **named block of code** that you can reuse whenever you want, instead of writing the same code over and over.


This is a function.

```python
def just_return_it(num):
    return num
````

This is a function to add 1

```python


def add_one(num):
  return num + 1

add_one(6)

print("add_one(6) returns:")
print(add_one(6))

````
This is a function to add 2

```python

def add_two(num):
  return num + 2


````
This is a function to multiply numbers

````python
def multiply_numbers(num_a, num_b):
  return num_a * num_b 

````

This is a function to add numbers

````python
def add_numbers(num_a, num_b):
  return num_a + num_b

````

| Code           | What is it?                                        |
| -------------- | -------------------------------------------------- |
| def            | `def` is a keyword that defines a new function     |
| add_one        | `add_one` is the function name                     |
| (num)          | `(num)` is the parameter list                      |
| num            | `num` is a parameter                               |
| :              | The `:` symbol indicates the body should start now |
| return num + 1 | `return num + 1` is a statement                    |
| num + 1        | `num + 1` is an expression                         |
| num            | `num` here is a variable                           |
| +              | `+` is an operator                                 |
| 1              | `1` is a literal number                            |

| Operator | Name               | Example   | Result | Explanation                                                                 |
|----------|--------------------|-----------|--------|-----------------------------------------------------------------------------|
| `+`      | Addition           | `5 + 2`   | `7`    | Adds the numbers together                                                   |
| `-`      | Subtraction        | `5 - 2`   | `3`    | Subtracts the right number from the left                                    |
| `*`      | Multiplication     | `5 * 2`   | `10`   | Multiplies the numbers                                                      |
| `/`      | Division           | `5 / 2`   | `2.5`  | Divides the left number by the right, result is a decimal (float)           |
| `//`     | Floor Division     | `5 // 2`  | `2`    | Divides and rounds *down* to the nearest whole number (ignores remainder)   |
| `%`      | Modulus (remainder)| `5 % 2`   | `1`    | Gives the remainder after division                                          |
| `**`     | Exponentiation     | `5 ** 2`  | `25`   | Raises the left number to the power of the right (here, 5 squared) 

### Expressions

An **expression** is any combination of values, variables, and operators that Python can evaluate to produce a result.

Example:

```python
2 + 3
````

**Precedence** determines the order in which Python evaluates operators in an expression. Operators with higher precedence are evaluated first.

```python
result = 2 + 3 * 4
print(result)  # 14, not 20
````

**State Tables**

```python
a = 10
b = 20
a = b
print(f"a is {a}")
print(f"b is {b}")

# The state is now:
# | Name | Value |
# | ---- | ----- |
# | a    | 20    |
# | b    | 20    |

````

## Two-Step Functions

## Using Multiple Statements
You can break a problem into steps by creating variables inside a function:

```python
def add_one_and_divide_by_two_with_statements(num):
    added = num + 1      # add 1 to the input
    halved = added / 2   # divide the result by 2
    return halved

print(add_one_and_divide_by_two_with_statements(5))  # 3.0
````
* num → parameter

* added → holds num + 1

* halved → holds added / 2

### Single Expressions

The same logic can be written more concisely with one return statement:
```python
def add_one_and_divide_by_two_with_an_expression(num):
    return (num + 1) / 2

print(add_one_and_divide_by_two_with_an_expression(5))
````

## Strings
**Strings are a data structure**

A string is a sequence of characters (letters).
* Using "double quotes"
* Or 'single quotes'

```python

my_name = "Becks"
print(my_name)

````
**Finding the Length of a String**

```python
length = len("Mooji Michael Anthony!")
print(f"The string is {length} characters long")
````
**Replace A String**

```python
old_string = "Hello, YOUR_NAME!"
new_string = old_string.replace("YOUR_NAME", "Kay")

print(new_string)
````

**Uppercase**

```python
def make_uppcase(string):
    return string.upper()
````

**Lowercase**

```python
def make_lowercase(string):
    return string.lower()
````

**Whitespace**
```python
def strip_whitespace(string):
  return string.strip()
````
# concatenation


🤝🏽 This means joining together.

We can join strings together in a few ways, here's one.

```python
my_string = "Ant" + "eater"
print(my_string)
```

_Note: you cannot concatonate a string and a number ("Forty) + 2). To make it do this, we need to explicitly convert the number to a string using the `str` function built into Python._

```python
my_string = "Forty" + str(2)
print(my_string)
````

### f-Strings

An f-string is another way to concatonate strings. They are a feature of Python 3.

```python
my_name = "Kay"
print(f"Hello, {my_name}!")
````

Note the `f` before the first quote, and the use of `{` and `}` to createspace you can put a variable into. In fact, you can put any expression in there:

```python
print(f"Your name is {len(my_name)} characters long")
````

It will also convert the number into a string so you don't have to.

f-strings are a form of what's called string interpolation.

# IF Statements


```python
if leaves_on_the_tree == 0:
  print("It must be winter — or a dead tree")
else:
  print("This is a happy tree with nice leaves")
```

Let's break this down:

The `if` keyword tells Python we want to execute some code conditionally.

* The `leaves_on_the_tree == 0` is the conditional expression. If this evaluates
to True, then the block of code afterwards will be run.

Within this, the `==` is a comparison operator. It evaluates to True if the values on the left and on the right are equal.

The colon `:` indicates the start of a new block of code.

The indented block of code after the if is the conditional block. Python will
run it if the condition evaluates to True.

When Python sees the `else:`, it will execute the next block of code only if the condition evaluated to False.

```python
print("")
print("Function: has_five_chars")

def has_five_chars(the_str):
  if len(the_str) == 5:
    return(f"{the_str} is five characters long")
  else:
    return("Not five characters")
````


# Python Comparison & Membership Operators

| Operator | Meaning                           | Example (`True` case)        | Notes |
|----------|-----------------------------------|-------------------------------|-------|
| `==`     | Equal to                         | `5 == 5` → `True`            | Values are the same |
| `!=`     | Not equal to                     | `5 != 3` → `True`            | Opposite of `==` |
| `>`      | Greater than                     | `7 > 3` → `True`             | Works with numbers |
| `<`      | Less than                        | `2 < 5` → `True`             | Works with numbers |
| `>=`     | Greater than or equal to         | `5 >= 5` → `True`            | Includes equality |
| `<=`     | Less than or equal to            | `3 <= 5` → `True`            | Includes equality |
| `in`     | Value exists inside another      | `"a" in "cat"` → `True`      | Checks membership in strings, lists, etc. |
| `not in` | Value does **not** exist inside  | `"z" not in "cat"` → `True`  | Opposite of `in` |

---

### Example function using `in`

```python
def a_is_within_b(a, b):
    return a in b

print(a_is_within_b("a", "cat"))  # True
print(a_is_within_b("z", "cat"))  # False

````

# Python Logical Operators

| Operator | Meaning            | Example (`True` case)          | Notes |
|----------|--------------------|--------------------------------|-------|
| `and`    | True if **both** conditions are True | `(5 > 2) and (3 < 4)` → `True` | Both sides must be True |
| `or`     | True if **at least one** condition is True | `(5 > 2) or (3 > 4)` → `True` | Only one side needs to be True |
| `not`    | Flips True ↔ False | `not (5 == 2)` → `True` | Negates the expression |
