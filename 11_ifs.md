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
