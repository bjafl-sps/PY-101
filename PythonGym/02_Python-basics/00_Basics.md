# EX_2.0: Warm up
Now we're getting started with the fun part! But before you working out your python muscles, let's get warmed up and familiar with the console and running basic python scripts.

## EX_2.0a: The Console
The console, also known as the terminal or command-line interface (CLI), is a text-based interface used to run commands, scripts, and manage files and directories. 

An interface is a bridge between the computer and the user. The console is a basic interface, that allows you to give the computer text based input and commands, and the computer can print out text based information to the user. Making a full graphical user interface (GUI) with windows, buttons and animations is a rather complex task. It's more user friendly, but you can achieve just as much with the console. 

All operating systems usually have a console interface, even though typical users only use the GUI on their devices. On Windows you can press `*winkey* + R` to open the run dialog, type in `cmd` and press enter. Now you will open a new console window.

Being a developer the console is your friend, allowing you to perform tasks more efficiently, running your beautiful scripts without the need to spend hours on making a GUI.


## EX_2.0b: Using the console
Let's start poking around in the console! 

- Assuming you are in Visual Studio code, go to ``Terminal -> New terminal``
- Now you will see a black window with some text below ⬇️. The text on the last line shows you the current working directory of the console.
- Try to type the command `dir` en press enter.
    - Now your computer should have printed a list of the files and subdirectories in the directory the console currently is working in. 
- Try to write `py --version`
    -   Now your computer will print the version of the currently selected python version on your computer, if it's installed correctly.

## EX_2.0c: Print
The `print()` command in Python is one of the most fundamental and commonly used functions, especially for beginners. It's the function you'll use to send output from your Python program to the console or terminal. This makes it an invaluable tool for everything from basic debugging to displaying program results or even user interfaces for command-line applications.

## EX_2.1: Create and run a python script
Time to create your very first python script! Assuming you've set up your environment in Visual Studio Code, it's time to start coding!

- First, right click on the folder *00_Put-your-solutions-here* to the left ⬅️
- Then click *New file...* and add type in a name, like `02_00_Basics.py`, and click enter.
> Please note the last part, `.py`. This tells the computer that the file you've crated contains python code.
- After you hit the enter key, the new file should open. 
- In this new file, write the following code:
```python
print('Hello world!')
```
> *Insights:*
>
> Please note all the parts in the above code. `print` is the function that tells the computer to print something to the terminal. The parenthesies encloses the information you want the `print`-function to process. The `'` at the beginning and end of *Hello world!* tells the computer to treat whats between as string (text) data.
>
> To summarize, the code above calls the `print`-function that tells the computer to output the information contained in the parenthesis, *Hello world!*, to the console.

- Now click the ▶️ icon in the top right part of your file window.
    - The python interpreter on your computer will now run this code, and you should see the text *Hello world!* being printed in the console window below ⬇️

## Well done!
Now you've created your very first python script! 🙌 In the next parts you'll utalize these basic skills to solve tasks. Remember the `print(...)` function, as you will use it in most excercises to print out your results.