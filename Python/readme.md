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

