#  How To Read Files Piece by Piece

The easiest way to read a file in chunks is to use a loop. First we will learn how to read a file line by line and then we will learn how to 
read it a kilobyte at a time. We will use a for loop for our first example:

```
handle = open("test.txt", "r")
for line in handle:
    print(line)
handle.close()

```
Here we open up a read-only file handle and then we use a for loop to iterate over it. You will find that you can iterate over all 
kinds of objects in Python (strings, lists, tuples, keys in a dictionary, etc).
That was pretty simple, right? Now let’s do it in chunks!

```
handle = open("test.txt", "r")
while True:
    data = handle.read(1024)
    print(data)
    if not data:
break


```

In this example, we use Python’s while loop to read a kilobyte of the file at a time. As you probably know, a kilobyte is 1024 bytes or characters.
Now let’s pretend that we want to read a binary file, like a PDF.

# How to Read a Binary File 

```
 handle = open("test.pdf", "rb")

```

So this time we changed the file mode to rb, which means read-binary. You will find that you may need to read binary files when you download 
PDFs from the internet or transfer files from PC to PC.
