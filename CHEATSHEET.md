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




