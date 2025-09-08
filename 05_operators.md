## [Operators](https://vimeo.com/954334235/902b0b036d#t=606)

**What is a logical operator**

Logical operators work on **boolean values** and let you combine them to make true / false statements.

I think we are actually working on **arithmetic operators** here.

A **boolean value** is the simplest kind of data in programming: it can only be `True` or `False`.
It's named after George Boole, the mathematician who created Boolean logic.
The data type is a `bool`


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



**Addition**

```python
added = 2 + 3
print(f"2 + 3 = {added} (should be 5)")
````
**Multiplication**

```python
multiplied = 2 * 3
print(f"2 * 3 = {multiplied} (should be 6)")
````

**Subtraction**

```python

subtracted = 2 - 3
print(f"2 - 3 = {subtracted} (should be -1)")

````
**Division**

```python

divided = 2 / 3
print(f"2 / 3 = {divided} (should be 0.6666666666666666)")

````
_This kind of 'decimal point' number, 0.6666666666666666 is called a float, by the way, meaning 'floating point'_

**Modulus**

Sometimes known as the "remainder if we divide 3 by 2"

```python

modulus = 3 %  2
print(f"3 %  2 = {modulus} (should be 1)")

````
**Floor Division**

Sometimes known as "division without the remainder"

```python

floor_divided = 2 // 3
print(f"2 // 3 = {floor_divided} (should be 0)")

````

**Exponentiation**

Sometimes known as "2 to the power of 3"

```python

expr = 2 ** 3
print(f"2 ** 3 = {expr} (should be 8)")

````

**Fun Facts**

**🦀 F-Strings**

An f-string is a Python feature that makes it easy to mix text with variables or calculations inside one string.

It is short for _formatted string literal_ and is a way to put a variable or expression directly inside a string.

**How To Write One**

You put an `f` in front of a string.

```python

f"some text {variable}"

````

Anything inside `{ ... } will be evaluated and replaced with its value.

```python


name = "Becks"
age = 41

print(f"My name is {name} and I am {age} years old.")

#Output

My name is Becks and I am 41 years old.


````
