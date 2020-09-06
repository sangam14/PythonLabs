# Using from to import

Some people don’t like having to preface everything they type with the module name. Python has a solution for that! You can actually 
import just the functions you want from a module. Let’s pretend that we want to just import the sqrt function:

```
from math import sqrt
print(sqrt(16)) # 4.0

```

This works pretty much exactly how it is read: from the math module, import the sqrt function. Let me explain it another way. We use Python’s 
from keyword to import the sqrt function from the math module. You can also use this method to import multiple functions from the math function:

```
from math import pi, sqrt
```
In this example, we import both pi and sqrt. If you tried to access pi you may have noticed that it’s actually a value and not a function that you can call.
It just returns the value of pi. When you do an import, you may end up importing a value, a function or even another module! 
There’s one more way to import stuff that we need to cover. Let’s find out how to import everything!

