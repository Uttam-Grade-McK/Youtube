# Python List/Array Built-in Methods

Python provides a set of built-in methods that you can use on lists/arrays:

| Method     | Description                                                      | Example                                                      |
|------------|------------------------------------------------------------------|--------------------------------------------------------------|
| `append()` | Adds an element at the end of the list                           | `my_list.append(4)` results in `[1, 2, 3, 4]`                |
| `clear()`  | Removes all the elements from the list                           | `my_list.clear()` results in `[]`                            |
| `copy()`   | Returns a copy of the list                                       | `new_list = my_list.copy()` results in a copy `[1, 2, 3]`    |
| `count()`  | Returns the number of elements with the specified value          | `my_list.count(2)` results in `1` (if 2 appears once)        |
| `extend()` | Adds the elements of a list (or any iterable) to the end of the current list | `my_list.extend([4, 5])` results in `[1, 2, 3, 4, 5]` |
| `index()`  | Returns the index of the first element with the specified value  | `my_list.index(3)` results in `2` (index of value 3)         |
| `insert()` | Adds an element at the specified position                        | `my_list.insert(1, 'a')` results in `[1, 'a', 2, 3]`         |
| `pop()`    | Removes the element at the specified position                    | `my_list.pop(2)` results in `[1, 2]` (removes item at index 2)|
| `remove()` | Removes the first item with the specified value                  | `my_list.remove(2)` results in `[1, 3]` (removes first occurrence of 2) |
| `reverse()`| Reverses the order of the list                                   | `my_list.reverse()` results in `[3, 2, 1]`                   |
| `sort()`   | Sorts the list                                                   | `my_list.sort()` results in `[1, 2, 3]`                      |





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

