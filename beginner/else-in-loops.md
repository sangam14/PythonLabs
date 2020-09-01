# What else is for in loops

The else statement in loops only executes if the loop completes successfully.
The primary use of the else statement is for searching for items:


```
my_list = [1, 2, 3, 4, 5]
for i in my_list:
    if i == 3:
        print("Item found!")
        break
    print(i)
else:
    print("Item not found!")

```

In this code, we break out of the loop when i equals 3. This causes the else statement to be skipped. If you want to experiment,
you can change the conditional to look for a value that’s not in the list, which will cause the else statement to execute. To be honest, 
I have never seen anyone use this structure in all my years as a programmer. Most of the examples I have seen are bloggers trying to explain
what it is used for. I have seen several who use it to raise an error if an item is not found in the iterable that you were searching. 
You can read a fairly in depth article by one of the Python core developers [here](https://ncoghlan-devs-python-notes.readthedocs.io/en/latest/python_concepts/break_else.html)

