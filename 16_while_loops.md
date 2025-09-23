# For Loops

[Vimeo](https://vimeo.com/954334424/6e40d11ef1#t=300)

```python

for letter in ["a", "b", "c"]:
  print(f"This letter is {letter}")

```


In everyday language: the Python for loop takes each item one by one and runs its block of code with that item.

And there's another Python helper that makes it even more useful:


```python
def print_numbers_in_range():
  for number in range(0, 10):
    print(f"This number is {number}")
````

`Range` more or less creates a list of the numbers from its first parameter to one below its last parameter. So: the numbers 0-9.

Compare it to a `while` version

```python
def print_numbers_in_range_with_a_while():
  number = 0
  while number < 10:
    print(f"This number is {number}")
    number = number + 1
````

The `for` and `range` version is a bit more concise.

## Three different ways to use Lists and Loops**

**➰ Summarising**

Using a loop to distil a list into one value.


**➰ Mapping**

Using a loop to convert each item to another item.

**➰ Filtering**

Using a loop to pick out only some items from a list.
