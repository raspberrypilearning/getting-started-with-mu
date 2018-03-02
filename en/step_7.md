## Code checking and debugging

### Highlighting

Mu will try and help you create code that works by highlighting errors, checking your code for errors and allowing you to debug.

The following line of code is incorrect.

```python
print("hello world)
```

There is a `"` missing at the end of `"hello world`

If you run this program you will receive an error:

```
File "c:\users\martin o'hanlon-lt\mu_code\hello.py", line 1
    print("hello world)
                      ^
SyntaxError: EOL while scanning string literal
```

Mu will highlight code which it recognises as not being correct.

![mu highlights error](images/mu_error.PNG)

### Checking

At any point you can also click the `Check` button, which will check your code for errors and provide advice.

![mu code check](images/mu_check.PNG)

When you have fixed an error, click `Check` again, to see if the problem disappears.

### Debugging

Unfortunately not all problems with code are syntax errors, some of them are bugs, your program runs fine, but it doesn't do what you want it to do.

Mu has a debugger which allows you to step through your code line by line and look at what it is doing.

This program should count down from 5 to 1:

```python
print("count down")
for count in range(5,1,-1):
    print(count)
```

But when it runs, it only counts down to 2:

```
count down
5
4
3
2
```

We can debug this program by putting a **breakpoint** into the code and using the **Debug** functions.

A breakpoint marks a line within your program where the debugger it will stop the program and wait.

+ Add a breakpoint to the code by clicking the line number 2.

A red circle will appear next to line 2.

![mu breakpoint](images/mu_breakpoint.PNG)

+ Click the **Debug** button to start the debugger.

The debugger will start and your program will run until it gets to your breakpoint.

![mu debugger](images/mu_debugger.PNG)

The line of code highlighted is the code which will be run next.

There are 4 buttons on the menu which allow you to control the debugger:

+ `Continue` - starts your program again, it will run until its hits a breakpoint or finishes.

+ `Step Over` - runs the next line of code in your program

+ `Step In` - if the next line of code is a function, it will *step in* the function and run it

+ `Step Out` - if the program is currently running a function, it will *step out* of the function and return to the line of code which called it.

There is also a `Debug Inspector` window of the right of the code which shows the current value of any variables being used.

+ Press `Step Over` to run the next line of code.

The count variable will appear in the debug inspector.

![mu debug inspector](images/mu_debugger2.png)

+ Keep pressing `Step Over` to run through each line of the program, you will see that `count` never reaches `1` because the `for` loop in the program should go to `0`:

```python
print("count down")
for count in range(5,0,-1):
    print(count)
```

