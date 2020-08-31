# Tuples

A tuple is similar to a list, but you create them with parentheses instead of square brackets. You can also use the tuple built-in. 
The main difference is that a tuple is immutable while the list is mutable. Let’s take a look at a few examples:

```
my_tuple = (1, 2, 3, 4, 5)
print(my_tuple[0:3]) # (1, 2, 3)
another_tuple = tuple()
abc = tuple([1, 2, 3])
print(abc)
  
```

The code above demonstrates one way to create a tuple with five elements. It also shows that you can do tuple slicing. However, you cannot sort a tuple! 
The last two examples shows how to create tuples using the tuple keyword. The first one just creates an empty tuple whereas the second example has three
elements inside it. Notice that it has a list inside it. This is an example of casting. We can change or cast an item from one data type to another. 
In this case, we cast a list into a tuple. If you want to turn the abc tuple back into a list, you can do the following:

```

abc = tuple([1, 2, 3])
abc_list = list(abc)
print(abc_list)


```
To reiterate, the code above casts the tuple (abc) into a list using the list
function.

