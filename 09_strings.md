# Strings

[Vimeo](https://vimeo.com/954334279/dd2abfbdd7#t=308)

A string is a sequence of characters (letters).
* Using "double quotes"
* Or 'single quotes'

A string is a type of **data structure**

```python

my_name = "Becks"
print(my_name)

````

A string has a number of characters inside it in a particular order.

This will access the first character.

```python
note = "The Most Perfect Crab"
print(note[0])
````

In coding we count form the zero - 'T' is the zeroth character.

And the last character: 

```python
print(note[-1])
````

## Get A Slice of the String

```python
print(note[0:3])
````

## Count the String
### This is an Independent Function

This uses a function pre-loaded into Python called `len`

```python
length = len("Mooji Michael Anthony!")
print(f"The string is {length} characters long")
````

## Replace the String
### This is a Method Function

```python

old_string = "Hello, YOUR_NAME!"
new_string = old_string.replace("YOUR_NAME", "Kay")
print(new_string)

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
