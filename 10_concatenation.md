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

