# greends-ipython 2023/2024

## Install Python 3 and Visual Studio Code (VS Code)

[Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial):
  * Python 3 interpreter; For Windows, download either from python.org or from the Microsoft Store; For macOS install Python using Homebrew; Linux: built-in Python 3 installation
  * VS Code; Download from VS code site
  * VS Code Python extension: A Visual Studio Code extension with rich support for the Python language (for all actively supported versions of the language: >=3.7), including features such as IntelliSense (Pylance), linting, debugging, code navigation, code formatting, refactoring, variable explorer, test explorer, and more!

## Python documentation and tutorials
The main tutorial for the class is [CS50P](https://cs50.harvard.edu/python/2022/weeks/).

You can find information on basic concepts and features of the Python language and system at  [The Python Tutorial at python.org](https://docs.python.org/3/tutorial/index.html). 

A nice interactive site is W3schools' [Python Tutorial](https://www.w3schools.com/python/default.asp) where you can find in particular an easy to use  [Python reference documentation](https://www.w3schools.com/python/python_reference.asp).

Another nice and very clear series of videos on Python are available in this Youtube channel: [Python Tutorials by Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU)

In particular, you might be interested in the following specific topics discussed in class:
* [text](https://docs.python.org/3/tutorial/introduction.html#text) and video [Python Tutorial for Beginners 2: Strings - Working with Textual Data](https://www.youtube.com/watch?v=k9TUPpGqYTo&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&index=2)
* [numbers](https://docs.python.org/3/tutorial/introduction.html#numbers) and video [Python Tutorial for Beginners 3: Integers and Floats - Working with Numeric Data](https://www.youtube.com/watch?v=khKv-8q7YmY&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&index=3)
* [f-strings and other formatting options](https://docs.python.org/3/tutorial/inputoutput.html);
* [Lists](https://docs.python.org/3/tutorial/introduction.html#lists) and video [Python Tutorial for Beginners 4: Lists, Tuples, and Sets](https://www.youtube.com/watch?v=W8KRzm-HUcc&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&index=4&t=1223s)
* [Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#dictionaries), see video [Python Tutorial for Beginners 5: Dictionaries - Working with Key-Value Pairs](https://www.youtube.com/watch?v=daefaLgNkw0&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&index=5&pp=iAQB)

## Class 1 (September 15, 2023)

1. [CS50P](https://cs50.harvard.edu/python/2022/weeks/0/), Section on "Functions, Variables"
   * **Do before next class.** [Shorts: Visual Code for CS50P](https://cs50.harvard.edu/python/2022/shorts/visual_studio_code_for_cs50/)
    
2. Some useful keyworks for the command line interface in terminal:
* `code filename.py` to create a new file 
* `ls` to list files in folder
* `cp filename newfilename` to copy a file, e.g. `cp ..\hello.py  farewell.py` (`..` represents parent folder)
* `mv filename newfilename` to rename or move file, e.g. `my farewell.py goodbye.py` or `mv farewell.py ..` (move one folder up)
* `rm filename` to delete (remove) file
* `mkdir foldername` to create new folder
* `cd foldername` change directory, e.g. `cd ..` 
* `rmdir foldername` to delete folder
* `clear` to clear terminal window

3. [CS50P](https://cs50.harvard.edu/python/2022/weeks/0/), Section on "Functions, Variables"
   * Notes: [Lecture 0](https://cs50.harvard.edu/python/2022/notes/0/)
    Creating Code with Python; 
    Functions; 
    Bugs; 
    Improving Your First Python Program:
        Variables,
        Comments,
        Pseudocode;
    Further Improving Your First Python Program;
    Strings and Parameters; 
        A small problem with quotation marks;
    Formatting Strings;
    More on Strings.

   
   * **Do before next class.** Video on [CS50 Video Player](https://video.cs50.io/JP7ITIXGpHk) or [YouTube](https://youtu.be/JP7ITIXGpHk): follow video and recreate exercises on VS Code up to 59' approximately (up to the section on integers 'int').
    
## Class 2 (September 22, 2023)

1. Questionnaire Q0 (test) on the topics of the previous class;
2. Work on [Problem set 0](https://cs50.harvard.edu/python/2022/psets/0/): "indoor voice", "playback speed", and "making faces". For this last one, check [the emoji chart](https://unicode.org/emoji/charts/full-emoji-list.html) and follow the instructions: Every emoji has a unique Unicode assigned to it. When using Unicode with Python, replace "+" with "000" from the Unicode. And then prefix the Unicode with "\\". For example, "U+1F605" will be used as "\U0001F605". But there are alternative ways to encode emojis in your Python code: check [this link](https://www.makeuseof.com/how-to-include-emojis-in-your-python-code/)
3. Presentation of topics to prepare for next class, namely Integers; Floats; Def; and Returning Values. How to organize a program with `main()` and auxiliary functions.
4. **Do before next class.** Complete [Lecture 0](https://cs50.harvard.edu/python/2022/notes/0/) and video [CS50 Video Player](https://video.cs50.io/JP7ITIXGpHk) until the end, on the following topics: Integers or int; Readability Wins; Float Basics; More on Floats; Def; Returning Values
5. **Do before next class.** Study [Lecture 1](https://cs50.harvard.edu/python/2022/notes/1/) up to "Modulo" and watch video  [CS50 Video Player: Lecture 1](https://video.cs50.io/_b6NgY_pMdw) up to approximately 34' on the topics: Conditionals, if Statements, Control Flow, or, and.

**All topics to prepare before next class**: *Integers or int; Readability Wins; Float Basics; More on Floats; Def; Returning Values; Conditionals, if Statements, Control Flow, or, and.*

## Class 3 (September 29, 2023)

1. Questionnaire Q1 on the topics of the homework;
2. Work on [Problem set 0](https://cs50.harvard.edu/python/2022/psets/0/): Einstein. Work on [Problem set 1](https://cs50.harvard.edu/python/2022/psets/1/): The Hitchhiker’s Guide to the Galaxy's Deep Thought, Home Federal Savings Bank, File Extensions.
3. Presentation of topics for next class:  Modulo; Creating Our Own Parity Function; Pythonic; match, Loops; While Loops; For Loops; Improving with User Input; More About Lists
Length (i.e. up to just before Dictionaries in Lecture 2)
5. **Do before next class.** Study the remainder of [Lecture 1](https://cs50.harvard.edu/python/2022/notes/1/) starting at "Modulo" and watch video  [CS50 Video Player: Lecture 1](https://video.cs50.io/_b6NgY_pMdw) after 34'.
6. **Do before next class.** Study [Lecture 2](https://cs50.harvard.edu/python/2022/notes/2/) up to "More about lists" and "Length" and watch video  [CS50 Video Player: Lecture 2](https://video.cs50.io/-7xg8pGcP6w) up to approximately 45'.
7. **Do before next class.** Try solving problems from [Problem Set 2](https://cs50.harvard.edu/python/2022/psets/2/): Camel; Coke Machine; Just setting up my twttr

**All topics to prepare before next class**: *Modulo; Creating Our Own Parity Function; Pythonic; match, Loops; While Loops; For Loops; Improving with User Input; More About Lists; Length*

## Class 4 (October 6, 2023)

1. Questionnaire Q2 on the topics of the homework;
2. Work on problems from [Problem Set 2](https://cs50.harvard.edu/python/2022/psets/2/): Camel; Coke Machine; Just setting up my twttr (P1: submit in Fenix one of those problems to be indicated in class)
3. Presentation of topics for next class:  TBC
6. **Do before next class.** Study remainder of [Lecture 2](https://cs50.harvard.edu/python/2022/notes/2/)  watch video  [CS50 Video Player: Lecture 2](https://video.cs50.io/-7xg8pGcP6w) starting at Dictionaries (~45').
7. **Do before next class.** [Lecture 3](https://cs50.harvard.edu/python/2022/notes/3/) and video [CS50 Video Player: Lecture 3](https://video.cs50.io/LW7g1169v7w)
8. **Do before next class.** Try solving problems from [Problem Set 3](https://cs50.harvard.edu/python/2022/psets/3/)
   
**All topics to prepare before next class**: *Dictionaries, More on code modularity (Mario example), Exceptions, Runtime Errors, try, else, Creating a Function to Get an Integer, pass*
