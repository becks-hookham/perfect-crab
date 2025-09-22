# While Loops

# Remember `if`s? Here's a reminder:

```python
my_name = "Kay"
if my_name == "Kay":
  print("Hello, Kay!")
else:
  print("Hello, you!")
````

**💻 The `if` is part of a catagory of programming tools knows as 'control flow'.**

These are tools that control the flow of execution in a program. The `if` controls which line gets executed.

💻There's another kind of control flow: **the loop.**

It comes it two varieties

➿ `for` loops

➿ `while` loops

**A while loop is perhaps the most simple**

```python
i = 0 # We call this the counter variable
while i < 10:
  print(f"The number is now {i}")
  i = i + 1
````

The`while` loop is like an `if`, in that it takes an expression that evaluatd to True or False, and then executes its block of code if the condition is True.

However, the `while` loop is different in that it keeps repeatedly executing the block for as long as the condition is True.

```python

print("")
print("Function: add_cats_repeatedly")

def add_cats_repeatedly(word_list, count):
  i = 0
  while i < count:
    word_list.append("cats")
    i = i + 1
  return word_list

````
