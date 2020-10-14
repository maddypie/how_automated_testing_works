## What is testing?
Simply put, making sure ouput recieved is the expected outcome is testing. Say, you define a function `append` which appends element into list.
```python3
def append(my_list: list, element):
    my_list.append(element)
    return my_list
```
To verify if this function gives output as expected, you may `print(my_list)` after passing a *test-list* and a *test-element*. This is called **manual testing**.
```python3
append([1, 2, 3], 4)
print(my_list)
# Out: [1, 2, 3, 4]
```
