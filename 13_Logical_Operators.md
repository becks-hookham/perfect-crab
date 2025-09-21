# Python Logical Operators

| Operator | Meaning            | Example (`True` case)          | Notes |
|----------|--------------------|--------------------------------|-------|
| `and`    | True if **both** conditions are True | `(5 > 2) and (3 < 4)` → `True` | Both sides must be True |
| `or`     | True if **at least one** condition is True | `(5 > 2) or (3 > 4)` → `True` | Only one side needs to be True |
| `not`    | Flips True ↔ False | `not (5 == 2)` → `True` | Negates the expression |



```python
def starts_with_x_or_y(the_str):
  first_letter = the_str[0]
  #                      VV look at this!
  if first_letter == "x" or first_letter == "y":
    return "It does!"
  else:
    return "It does not."

````

