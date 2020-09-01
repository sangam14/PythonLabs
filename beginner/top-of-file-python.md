
# if __name__ == “__main__”

Does your Python program always starts at the top of the python file  or can you tell Python where to start? Let's find out!

you will see a very common conditional statement used in many Python examples. This is what it looks like:

```
if __name__ == "__main__":
    # do something!

```
You will see this at the end of a file. This tells Python that you only want to run the following code if this program is executed as 
a standalone file. I use this construct a lot to test that my code works in the way I expect it to. whenever you create a Python script,
you create a Python module. If you write it well, you might want to import it into another module. When you do import a module,
it will not run the code that’s under the conditional because __name__ will no longer equal "__main__".

