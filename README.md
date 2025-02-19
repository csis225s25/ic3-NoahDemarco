# In Class Problem Set 3

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**

The changes I made included removing static context from our instance variables, Added an identifier creating JComboBox, and finally there was no constrcutor, so like lab I moved what was in main to a constructor and kept main for just running the program.

**What caused it to stop working?**

In older versions, one could not need a constructor when dealing with genric types but I think the reason for the code not working was because we were using a generic class with no constructor, as well as static context issuses and identifier.
