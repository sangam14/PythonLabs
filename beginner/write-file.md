
# Writing Files in Python
- If you have been following along, you can probably guess what the file-mode flag is for writing files:
“w” and “wb” for write-mode and write-binary-mode. Let’s take a look at a simple example, shall we?

- CAUTION: When using “w” or “wb” modes, if the file already exists, it will be overwritten with no warning! You can check if 
a file exists before you open it by using Python’s os module.

```
handle = open("test.txt", "w")
handle.write("This is a test!")
handle.close()
# Now let's read the file that we just wrote
handle = open("test.txt", "r")
for line in handle:
    print(line)
handle.close()

```

That was easy! All we did here was change the file mode to “w” and we called the file handle’s write method to write some text to 
the file. The file handle also has a writelines method that will accept a list of strings that the handle will then write to disk in order.


