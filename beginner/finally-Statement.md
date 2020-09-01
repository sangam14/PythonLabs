# The finally Statement

The finally statement is really easy to use. Let’s take a look at a silly example:

```
my_dict = {"a":1, "b":2, "c":3}
try:
    value = my_dict["d"]
except KeyError:
    print("A KeyError occurred!")
finally:
    print("The finally statement has executed!")


```

If you run the code above, it will print the statement in the except and the finally. This is pretty simple, right? Now you can use the finally 
statement to clean up after yourself.You would also put the exit code at the end of the finally statement.

