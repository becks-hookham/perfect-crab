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
