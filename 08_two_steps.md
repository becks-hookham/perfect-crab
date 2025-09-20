# Two-Step Functions

Here's a function: 

```python

def add_one_and_divide_by_two_with_statements(num):
  added = num + 1
  halved = added / 2
  return halved

print("add_one_and_divide_by_two_with_statements(5) is:")

print(
  add_one_and_divide_by_two_with_statements(5)
)

````

**(num)** = parameter

**added =**

= creating a variable inside the function and assigning to it the result of adding 1 to (num)

**halved =**

= Created a new variable which is added / 2

**answer** = 3

## You can do this with a single expression

```python
def add_one_and_divide_by_two_with_an_expression(num):
  return (num + 1) / 2

print("add_one_and_divide_by_two_with_an_expression(5) is:")

print(
  add_one_and_divide_by_two_with_an_expression(5)
)
````
