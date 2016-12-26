# Teach Girl Friend Python

My girl is HR, but she wants to learn some programming. So Python~

## Skeleton

 - Lesson 1: **Python in terminal**
   - Shell and terminal
     - Terminal is the outter app
     - Shell is the software run within terminal
     - We use [bash][bash], because Bourne Again improved SHell.
   - What is file path
     - It's something like `/Users/liriansu`
     - Very alike Windows's `C:\\Users\\liriansu`
   - Run python in terminal
     - Just simply type `python`
     - You can only modify current line
     - Because it's command history, just as chat history in wechat
   - Why code style is important
     - This is some agreements
     - We write code for humans to read
   - Let's type a sample python program
     - This program calculate the sum of [1, 100]
     - Gauss did this very young

Wrong:
```
s=0
for x in range(1,101):
    s=s+x
    print s
```

Correct:
```
    s = 0
    for x in range(1, 101):
        s = s + x
    print s
```

 - Lesson 2: **Statement, function, and modules(libraries)**
   - Function `sum` shorten our long program
   - Function `input` make program flexible
   - Builtin functions
   - Statement `for` and `print`
     - Python 2.7, Python 3.6
   - Re-usable function save our life
   - Programming encourage us to use others' code
     - Statement `import`
     - Easter eggs: `import this` and `import antigravity`
     - This is python :evil:
     - Shell command `pip install xlrd`
   - Module `datetime`
     - `datetime.date.today()`
     - `datetime.date(year, month, day)`
     - `(datetime_x - datetime_y).days`
   - Google is best teacher

[bash]: https://www.gnu.org/software/bash/
