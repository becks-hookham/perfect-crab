# Lists

💻 A list is another type of **data structure**

💻 A list is essentially a sequence of items that can be of any type/

```python
my_favourite_numbers = [1, 3, 5, 7, 9]
my_friends = ["Victoria", "Mel", "Melanie", "Emma"]
````

⚠️ Notice the **[square brackets]** that tell Python it's a list
⚠️ It's really easy to forget the **commas**

## Indexing

👉🏼 You can index into lists- which basically means point to an item.

````python
my_list = [44, 35, 21, 63]
my_list[0]   # Evaluates to 44
my_list[-1]  # Evaluates to 63
my_list[1:3] # Evaluates to [35, 21]
````

## List Modifications

💻 These are inbuilt Python functions

### APPEND

It adds an item to the list!

```python
my_list = ["a", "b", "c"]
my_list.append("d")
print(my_list) # my_list is now ["a", "b", "c", "d"]
```

If you want to keep a copy of the list without it magically altering the first list:

```python
my_list = ["a", "b", "c"]
my_copy = my_list.copy()
my_copy.append("d")
print(my_list) # my_list is still ["a", "b", "c"]
print(my_copy) # my_copy is now   ["a", "b", "c", "d"]
```
[More inbuilt python functions](https://docs.python.org/3/tutorial/datastructures.html)
