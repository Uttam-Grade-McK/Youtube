# 📋 Python List/Array Built-in Methods

Python provides a set of built-in methods that you can use on lists/arrays:

| Method     | Description                                                      | Example                                                      |
|------------|------------------------------------------------------------------|--------------------------------------------------------------|
| `append()` | ➕ Adds an element at the end of the list                         | `my_list.append(4)` ➡️ `[1, 2, 3, 4]`                        |
| `clear()`  | 🗑️ Removes all the elements from the list                        | `my_list.clear()` ➡️ `[]`                                    |
| `copy()`   | 📋 Returns a copy of the list                                     | `new_list = my_list.copy()` ➡️ `[1, 2, 3]`                   |
| `count()`  | 🔢 Returns the number of elements with the specified value        | `my_list.count(2)` ➡️ `1` (if 2 appears once)                |
| `extend()` | ➡️ Adds the elements of a list (or any iterable) to the end of the current list | `my_list.extend([4, 5])` ➡️ `[1, 2, 3, 4, 5]` |
| `index()`  | 🔍 Returns the index of the first element with the specified value | `my_list.index(3)` ➡️ `2` (index of value 3)                 |
| `insert()` | 📝 Adds an element at the specified position                      | `my_list.insert(1, 'a')` ➡️ `[1, 'a', 2, 3]`                 |
| `pop()`    | 🎯 Removes the element at the specified position                  | `my_list.pop(2)` ➡️ `[1, 2]` (removes item at index 2)       |
| `remove()` | ❌ Removes the first item with the specified value                | `my_list.remove(2)` ➡️ `[1, 3]` (removes first occurrence of 2) |
| `reverse()`| 🔄 Reverses the order of the list                                 | `my_list.reverse()` ➡️ `[3, 2, 1]`                           |
| `sort()`   | 🗂️ Sorts the list                                                | `my_list.sort()` ➡️ `[1, 2, 3]`                              |





# Python Dictionary Built-in Methods

Python provides a set of built-in methods that you can use on dictionaries:

| Method        | Description                                                                                  | Example                                                      |
|---------------|----------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| `clear()`     | Removes all the elements from the dictionary                                                 | `my_dict.clear()` results in `{}`                            |
| `copy()`      | Returns a copy of the dictionary                                                             | `new_dict = my_dict.copy()` results in a copy `{'a': 1, 'b': 2}` |
| `fromkeys()`  | Returns a dictionary with the specified keys and value                                       | `dict.fromkeys(['a', 'b'], 0)` results in `{'a': 0, 'b': 0}` |
| `get()`       | Returns the value of the specified key                                                       | `my_dict.get('a')` results in `1`                            |
| `items()`     | Returns a list containing a tuple for each key-value pair                                    | `my_dict.items()` results in `[('a', 1), ('b', 2)]`          |
| `keys()`      | Returns a list containing the dictionary's keys                                              | `my_dict.keys()` results in `dict_keys(['a', 'b'])`          |
| `pop()`       | Removes the element with the specified key                                                   | `my_dict.pop('a')` results in `1` and `my_dict` becomes `{'b': 2}` |
| `popitem()`   | Removes the last inserted key-value pair                                                     | `my_dict.popitem()` results in `('b', 2)` and `my_dict` becomes `{'a': 1}` |
| `setdefault()`| Returns the value of the specified key. If the key does not exist: insert the key, with the specified value | `my_dict.setdefault('c', 3)` results in `{'a': 1, 'b': 2, 'c': 3}` |
| `update()`    | Updates the dictionary with the specified key-value pairs                                    | `my_dict.update({'c': 3})` results in `{'a': 1, 'b': 2, 'c': 3}` |
| `values()`    | Returns a list of all the values in the dictionary                                           | `my_dict.values()` results in `dict_values([1, 2])`          |




# Python Tuple Built-in Methods

Python provides two built-in methods that you can use on tuples:

| Method     | Description                                                                       | Example                                                      |
|------------|-----------------------------------------------------------------------------------|--------------------------------------------------------------|
| `count()`  | Returns the number of times a specified value occurs in a tuple                   | `my_tuple.count(2)` results in `1` (if 2 appears once)       |
| `index()`  | Searches the tuple for a specified value and returns the position of where it was found | `my_tuple.index(3)` results in `2` (index of value 3)         |




# 🐍 Python Set Built-in Methods

Python provides a set of built-in methods that you can use on sets:

| Method                        | Shortcut | Description                                                                       | Example                                                      |
|-------------------------------|----------|-----------------------------------------------------------------------------------|--------------------------------------------------------------|
| `add()`                       | ➕       | Adds an element to the set                                                        | `my_set.add(4)` ➡️ `{1, 2, 3, 4}`                            |
| `clear()`                     | 🗑️       | Removes all the elements from the set                                             | `my_set.clear()` ➡️ `set()`                                  |
| `copy()`                      | 📋       | Returns a copy of the set                                                         | `new_set = my_set.copy()` ➡️ `{1, 2, 3}`                     |
| `difference()`                | ➖       | Returns a set containing the difference between two or more sets                  | `my_set.difference(another_set)` ➡️ `{1}` (if `my_set` is `{1, 2, 3}` and `another_set` is `{2, 3, 4}`) |
| `difference_update()`         | `-=`     | Removes the items in this set that are also included in another, specified set    | `my_set.difference_update(another_set)` ➡️ `{1}`             |
| `discard()`                   | ❌       | Remove the specified item                                                         | `my_set.discard(2)` ➡️ `{1, 3}`                              |
| `intersection()`              | 🔀       | Returns a set, that is the intersection of two other sets                         | `my_set.intersection(another_set)` ➡️ `{2, 3}`               |
| `intersection_update()`       | `&=`     | Removes the items in this set that are not present in other, specified set(s)     | `my_set.intersection_update(another_set)` ➡️ `{2, 3}`        |
| `isdisjoint()`                | ❓       | Returns whether two sets have an intersection or not                              | `my_set.isdisjoint(another_set)` ➡️ `False`                  |
| `issubset()`                  | 👇       | Returns whether another set contains this set or not                              | `my_set.issubset(another_set)` ➡️ `True`                     |
| `<`                           | ⬇️       | Returns whether all items in this set are present in another, specified set(s)    | `my_set < another_set` ➡️ `True`                             |
| `issuperset()`                | 👆       | Returns whether this set contains another set or not                              | `my_set.issuperset(another_set)` ➡️ `False`                  |
| `>`                           | ⬆️       | Returns whether all items in another, specified set(s) are present in this set    | `my_set > another_set` ➡️ `False`                            |
| `pop()`                       | 🎯       | Removes an element from the set                                                   | `my_set.pop()` removes and returns a random element          |
| `remove()`                    | 🚮       | Removes the specified element                                                     | `my_set.remove(2)` ➡️ `{1, 3}`                               |
| `symmetric_difference()`      | 🔄       | Returns a set with the symmetric differences of two sets                          | `my_set.symmetric_difference(another_set)` ➡️ `{1, 4}`       |
| `symmetric_difference_update()`| 🔁       | Inserts the symmetric differences from this set and another                       | `my_set.symmetric_difference_update(another_set)` ➡️ `{1, 4}`|
| `union()`                     | 🔗       | Return a set containing the union of sets                                         | `my_set.union(another_set)` ➡️ `{1, 2, 3, 4}`                |
| `update()`                    | 🔧       | Update the set with the union of this set and others                              | `my_set.update(another_set)` ➡️ `{1, 2, 3, 4}`               |




