# import this

Python provides the import keyword for importing modules. Let’s give it a try:

```
import this

```
If you run this code in your interpreter, you should see something like the following as your output:

```
The Zen of Python, by Tim Peters
Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!

```

You have found an “Easter egg” in Python known as the “Zen of Python”. It’s actually a sort of an unofficial best practices for Python. 
The this module doesn’t actually do anything, but it provided a fun little way to show how to import something.
Let’s actually import something we can use, like the math module:

```
import math
print(math.sqrt(4))
# 2.0

```

Here we imported the math module and then we did something kind of new. We called one of its functions, sqrt (i.e. square root).
To call a method of an imported module, we have to use the following syntax: module_name.method_name(argument). In this example, 
we found the square root of 4. The math module has many other functions that we can use, such as cos (cosine), factorial, log (logarithm), etc. 
You can call these functions in much the same way you did sqrt. The only thing you’ll need to check is if they accept more arguments or not. 
Now let’s look at another way to import.
