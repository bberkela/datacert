# datacert
Data Certificate Program
# April 9, 2018 
# Files for homework for Course 5 Task 1 UT Data Certificate Program
#########################3
# Folder Includes:



## REPORT ###

######################################################################
# ERRORS & WARNING MESSAGES
######################################################################

# The errors/warning messages that you encountered and how you overcame them (these should be in the form of markdown cells)
# NOTE: E stands for error

# E1) Warned me that there was a new version of pip (couldn't copy and paste from command line yet)
  # Updated pip following instructions on screen. Received one "syntax" error messages because I was not in the right folder
  # for the python installation. "'python' is not recognized as an internal or external command, operable program or batch file."
  # Took less than minutes to get to the right path, update pip and confirm that all the other
  # Anaconda items were up-to-date.
  
# E2) Warning in Jupyter Notebooks (missing parathenses). Easy to fix. Me trying to remember print commands from Python after a long day
# day of work. Easy to fix. Followed instructions
  # 
  # File "<ipython-input-23-826950f270bd>", line 2
    # print myStrong
  # SyntaxError: Missing parentheses in call to 'print'. Did you mean print(myStrong)?

# E3) Warning because didn't import a module
# ---------------------------------------------------------------------------
# NameError                                 Traceback (most recent call last)
# <ipython-input-34-e51eb2b679f5> in <module>()
#      1 # get current time
# ----> 2 datetime.datetime.now()
  # NameError: name 'datetime' is not defined
  
# E4) Typo type errors
#  File "<ipython-input-48-6391e2faf08e>", line 6
  #  return Value1 + Value 2
                          ^
# SyntaxError: invalid syntax
# Simply retyped the typo. Go back and quickly check. Syntax errors simply to fix
# Python is Case Sensitive


# E5) Intentionally provided only one argument to create error as requested in Ch. 4 Tutorial

# Trying DoSum with one argument to create an error message
# def DoSum(1,2)
# Trying DoSum with one argument to create an error message
# def DoSum(1,2)
  # File "<ipython-input-50-08a642cece8a>", line 2
    # def DoSum(1,2)
              ^
# SyntaxError: invalid syntax

# E6) Error "unexpected EOF"

# def DisplaySum(Value1, Value2):
  #  print(str(Value1) + ' + ' + str(Value2) + ' = ' +
  #  str((Value1 + Value2))
# sending argument bey keywords so you don't necessarily have to have the values in order needed
# def DisplaySum(Value1, Value2):
  #  print(str(Value1) + ' + ' + str(Value2) + ' = ' +
  #  str((Value1 + Value2))
  # File "<ipython-input-60-da4861838ef2>", line 4
    # str((Value1 + Value2))                  ^
# SyntaxError: unexpected EOF while parsing
# Needed extra ) because of end of file issue


# E7) Got a syntax error on page 72 with the code. 
# I typed Var Args as written but thought it seemed weird that it had a space
# got syntax error. Took out space. Typo in textbook.


#E8) Atom the texteditor I used to first learn python automatically indents the code correctly. Jupyter notebooks does not
# This error resulted from having the indents off in my code. Quick fix one I realized the "else" was the syntax error
# File "<ipython-input-90-a44759eb46f8>", line 8
    # else:
       ^
# SyntaxError: invalid syntax

# E9 No module named sets
# ModuleNotFoundError                       Traceback (most recent call last)
# <ipython-input-102-9bf5d7da6c32> in <module>()
  #    3 
  #    4 # import library
# ----> 5 from sets import Set
  #    6 SetA = Set(['Red', 'Blue', 'Green', 'Black'])
  #    7 SetB = Set(['Black', 'Green', 'Yellow', 'Orange'])

ModuleNotFoundError: No module named 'sets'

########################################################################
# Was it straightforward to install Python and all of the libraries?
########################################################################

# Yes. Python, pip and related support systems in Anacondan required updates based on a warning message in Command Prompt
  # Followed instructions to update PIP. Everything else was up-to-date (See aabove)
  # Accidentally tried to install from wrong folder at first. Needed to ensure was in the correct folder using cd.. But minor issue. 
  # Numpy, SciPi, and MatLab libraries all installed simply. Received confirmation that they worked (i.e., "Requirement already   
  # satisfied:") 

  # NOTE:  SciPi did not require the complicated steps listed in instructions
  # C:\Program Files>pip install scipy
  # Requirement already satisfied: scipy in c:\programdata\anaconda3\lib\site-packages

  # NOTE: 
  # In Windows 10 for install remember that people need to run the command prompt as an Administrator (Right Click)


########################################################################
# Was the tutorial useful? Would you recommend it to others?
########################################################################

# Useful. I suspect it would be difficult for someone who had never coded before and absolute beginner
# or someone with limited coding experience. 



########################################################################
# What are the main lessons you've learned from this experience?
########################################################################
 
# Keep learning shortcut keys so you don't have to use mouse (I love to do everything by keyboard
# Sometimes if I just don't think about it, I figure it out quickly

# Jupyter notebook is nice for starting out in some ways, but I prefer creating on a different text editor (ATOM)
# and then running in command line. Why? It indents automatically.
# Both use nice color-coded coded. Which helps in reading the code, although the colors aren't consistent

# Strategies I use for proofing code and documents (start at the end and move backward, help simply the 
# process of cleaning code. Catch more errors this way.
