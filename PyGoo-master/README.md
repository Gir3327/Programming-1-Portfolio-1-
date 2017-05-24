***
![Python](http://www.python.org/images/python-logo.gif)

Python, another object-oriented scripting language, was released publicly in 1991. Developed by Guido van Rossum of the National Research Institute for Mathematics and Computer Science in Amsterdam (CWI), Python draws heavily from Modula-3—a systems programming language. Python is “extensible”—it can be extended through classes and programming interfaces.

### What this page IS:
* A reference for beginners
* A place to prepare for the State Test
* A collaborative resource for students 

### And what this page IS NOT:
* A comprehensive site for the language (there will be plenty of links for that)
* A place to delete entries by students (leave that to Kapptie)
* A collection of copyrighted material

***
### Version Notes:
Though Python version 3 is alive and well, 2.7 remains the production version and is what we will use in the 2014 Programming course.

### Installers
* [Python 2.7.6](http://www.python.org/download/releases/2.7.6/) - Note: if you are installing PyGame, choose 32bit version
* [PyGame](http://www.pygame.org/download.shtml) - Note: choose 32bit Python 2.7
* [Sublime Text 2](http://www.sublimetext.com/) - Very nice code editor.

### Environment

### IDLE Shell
* Start Python: After installation you can start Python from the start menu. You can interact with Python through the interpreter or use the code editor to create and save files with the py or other extensions. 

### Windows Command Prompt

Here is a great free e-book on the command line: [Conquering the Command Line](http://conqueringthecommandline.com/book)

* Navigate into a working directory using: cd 
* Navigate back a directory using: cd..
* Auto complete long file/folder names: tab
* List directory contents: dir
* Navigate to the Python install directory: C:\Program Files\Python
* Execute the program: python Filename.py
* Start the interpreter in terminal: python
* Quit the interpreter: quit()
* Help in the interpreter: help()

### Linux/Mac Terminal
* Navigate into a working directory using: cd 
* Navigate back a directory using: cd ..
* Auto complete long file/folder names: tab
* List director contents: ls
* Execute the program: python Filename.py
* Start the interpreter in terminal: python
* Quit the interpreter: quit()
* Help in the interpreter: help()

***
### What
Python is a widely used general-purpose, high-level programming language.

### When
### Where
### Why
### How

***
### Web
Various web resources geared to those with limited or no experience programming. Feel free to add NON-advanced Python resources as you wish.

### Online Courses
* [Codeacademy](http://www.codecademy.com/tracks/python) * Required
* [Google's Python Class](https://developers.google.com/edu/python/)
* [Python Training](https://wiki.python.org/moin/PythonTraining)
* [The Standard Python Library](http://www.effbot.org/zone/librarybook-index.htm)
* [Khan Academy](https://www.khanacademy.org/science/computer-science-subject/computer-science)

### Online Reference
* [Python Basics Cheat Sheet](http://www.astro.ufl.edu/~warner/prog/python.html)
* [Official 2.7.6 Documentation](http://docs.python.org/2/)
* [Python 2.7 Quick Reference](http://rgruet.free.fr/PQR27/PQR2.7.html) * AWESOME!
* [Data Structures and Algorithms](http://www.brpreiss.com/books/opus7/html/book.html)
* [TutorialsPoint](http://www.tutorialspoint.com/python/index.htm) * EXCELLENT!
* [Pygame Official Documentation] (http://www.pygame.org/docs/)

### Video
* [Bucky's Python](http://www.youtube.com/watch?v=4Mf0h3HphEA&list=PL0213E8DC3AA8E21B): More than 35 vids, he likes Windows
* [Google Python Class](http://www.youtube.com/watch?v=tKTZoB2Vjuk)
* [Python Programming Intro](http://www.youtube.com/watch?v=72RKMMyLxS8)
* [Python Training - Getting Started with Python](http://www.youtube.com/watch?v=B9MvjMFokLc)

### User Forums
* [Python Magazine](http://www.pythonmagazine.com)
* [The Python Papers Anthology](http://ojs.pythonpapers.org)
* [Python Rag](http://www.pythonrag.org)
* [Utah Python User Group](http://utahpython.org)

### Wikis
* [The Game Programming Wiki](http://www.gpwiki.org)
* [Official Python Wiki](https://wiki.python.org/moin/)

### Printed
Resources you can pickup at the library or from your favorite bookstore. Books with a decent reputation for teaching beginners. Please refrain from adding advanced topics.
## Books
* [Core Python](http://corepython.com)
* [Dive Into Python](http://www.diveintopython.net): Free online text
* [Head First Python](http://shop.oreilly.com/product/0636920003434.do)
* [Learning Python 5th](http://shop.oreilly.com/product/0636920028154.do): * Official Programming 1B Text
* [More Python Programming](http://www.delmarlearning.com/companions/index.asp?isbn=1435459806)
* [Programming Python 4th](http://shop.oreilly.com/product/9780596158118.do)
* [Python: Visual QuickStart Guide 3rd](http://www.peachpit.com/store/python-visual-quickstart-guide-9780321929556)
* [Think Python: How to Think Like a Computer Scientist](http://www.greenteapress.com/thinkpython/thinkpython.pdf)
* [How to Think Like a Computer Scientist: Learning with Python](http://www.greenteapress.com/thinkpython/thinkCSpy/)
* [Python for Fun](http://www.openbookproject.net/py4fun/)
* [Invent Your Own Computer Games With Python](http://inventwithpython.com/)
* [Thinking in Python](http://www.mindview.net/Books/TIPython/)
* [The Django Book](http://www.djangobook.com/en/2.0/index.html)
* [Snake Wrangling for Kids](http://www.briggs.net.nz/snake-wrangling-for-kids.html)
* [Natural Language Processing with Python](http://www.nltk.org/book)

A collection of tips, tricks, best practices and those rare "ah ha" moments that open doors to productivity. Try to categorize the type of point you are spotlighting on this page. Initial your comments at the end of each line.

### Environment

### Syntax
How about the "for else"
```python
from random import randrange
n = 5
foo = [randrange(10) for i in range(n)]
for i in foo:
    if i == 0:
        print('found 1')
else:
    print('did not find 1')
```


# Structure
# Random Element from an Array
```python
import random
random.choice (mylist)
# Populate A List with Loop
myList = (random.random() for x in xrange(3))
for r in myList:
```

### Fun

### Python Type System: 
Note: lists, dictionaries and tuples are covered in their own section.

#### [Numbers](http://www.tutorialspoint.com/python/python_numbers.htm)

#### [Strings](http://www.tutorialspoint.com/python/python_strings.htm)

#### Tuples

#### Dictionaries

#### Mutable Sequences
A mutable sequence is a collection of alphanumeric values that CAN change after they are created.

#### Immutable Sequences
An immutable sequence is a collection of alphanumeric values that CANNOT change after they are created.
