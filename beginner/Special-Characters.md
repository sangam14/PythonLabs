# Special Characters
How are we going to print special characters like new line and tabs etc. in Python?

Strings can contain special characters, like tabs or new lines. We need to be aware of those as they can sometimes crop up and cause problems. 
For example, the new line character is defined as “n”, while the tab character is defined as “t”. 
Let’s see a couple of examples so you will better understand what these do:

```
print("I have a \n new line in the middle")
print("This sentence is \ttabbed!")

```
- Was the output as you expected? In the first example, we have a “n” in the middle of the sentence, which forces it to print out a new line. 
Because we have a space after the new line character, the second line is indented by a space. The second example shows what happens when we have 
a tab character inside of a sentence.

- Sometimes you will want to use escape characters in a string, such as a backslash. To use escape characters, you have to actually use a backslash, 
so in the case of a backslash, you would actually type two backslashes. Let’s take a look:

```
print("This is a backslash \")

```
You will notice that the first example didn’t work so well. Python thought we were escaping the double-quote,
so it couldn’t tell where the end of the line (EOL) was and it threw an error. The second example has the backslash 
appropriately escaped.

```
print("This is a backslash \\")
```
