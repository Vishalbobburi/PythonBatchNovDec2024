# PythonBatchNovDec2024
A repository with all the classes material for becoming a python developer

Git commands
To clone a repository (not needed in codespace, needed for local development):

git clone https https://github.com/udhayprakash/PythonBatchNovDec2024.git
To list the local branches:

git branch
To create a branch:

git checkout -b class01
To see the latest local changes:

git status
To check/verify the modified content in existing file,

git diff 
To stage the changes:

git add <filename>
To commit the changes:

git commit -m "commit message"
To push the changes,

git push origin <sourceBRanch>

    class01 -> main
    ex: git push origin class01
Daily
To check the branch is clean,

git status 
To checkout to the main branch

git checkout main 
To get the latest changes

git pull origin main 
To create new branch

git checkout -b <NEW BRANCH NAME>
Virtual Environment
Isolated environment 

why needed
    - same system, multiple projects
        - different python versions 
        - same python verison, but differenet module versions

How to create Virtual Environment 
    - Virtualenv
    - venv
    - pipenv
    - poetry 
    - uv

Using Virtualenv
    
    Install
        pip install virtualenv
    
    create virtual environment
        python -m virtualenv .venv
    
    activate virtual environment
        linux
            source .venv/bin/activate

        windows
            .venv/script/activate
Course Completed
class00 04th Nov 2024

00. Dev Setup
    Installing IDE/Editor
    Installing Python and local setup
    Github access, creating project
class01 06th Nov 2024

    git commands
    markdown syntax
    daily activity and usage

01.Introduction
    Importance of Python
    Two versions of Python (2.x & 3.x)
class02 11th Nov 2024

    PEP 8 Guidelines (https://peps.python.org/pep-0008/)
    Shebang line
    Indendation Issue and best practices
    built-in functions
    print function
    Script mode vs interactive mode
    Jupyter notebook usage
    Ascii and Unicode characters
class03 13th Nov 2024

    Comment Operator
    keywords and Identifiers
    Line continuation and statement separator operators

02.Basics
    Arithmetic operations
        +, -, , /, //, %, *
        divmod() function
        compound opertions

Assignments:

    1) try to the sum of digits in a integer number, using divmod()
    2) If a clock has revolved for 32 times, and is half way, how many days completed
class04 15th Nov 2024

        Practical Problem solving
        working with complex numbers
        abs() function
        Operator precedence in Arithmetic operations

Assignments:

    1) savings Bank 
    2) Bank loan
        simple interest 
        compund interest
    3) convert from hex to oct , and vice versa
    4) feet to cms conversion
class05 20th Nov 2024

String operations
    Usage of single, double and triple quotes
    len() function
    Indexing and Slicing Strings
class06 22nd Nov 2024

    string attributes
class07 25th Nov 2024

    string attributes
class08 27th Nov 2024

    String formatting: old & new styles, f-strings
    unicode strings
class09 29th Nov 2024

    bytearray() and byte() strings
    Usage of help
    Usage of pydoc

03.Language Components
    Relational Operations
    Logical Operations
class10 2nd Dec 2024

    Boolean Operations
    Bitwise Operations
    Identity Operations
        Dual Memory management Strategy
    range() function
    Conditional Operations
class11 2nd Dec 2024

    Structural Pattern Matching
    Loops: for & while, break, continue, pass, sys.exit
# Assignment: Try these break, continue, pass, on a for loop example
class12 6th Dec 2024

    Walrus Operator

04.Exception Handling
    Exceptions Hierarchy
    Different types of errors, error vs exception and exception groups
    Handling single and multiple exceptions
    raising exceptions
    asserts
    traceback
    exception Groups
    warnings
class13 9th Dec 2024

05.Debugging
    Importance of logical errors
    Debugging with pydevd
    Debugging with pdb, ipdb
    breakpoint() function
    PYTHONBREAKPOINT environment variable usage
    post analyses of executed script
class14 10th Dec 2024

06.Collections
    Lists
class15 11th Dec 2024

    Copy Problem - shallow copy vs deepcopy
    Tuples & namedtuples
    Immutability & unpacking
    Sets
        attributes, operations
class16 13th Dec 2024

    fronzensets
    Dictionaries
        zip() function
        workaround for switch case
    Comprehensions
    Working with Iterables - sum(), max(), min()
class17 16th Dec 2024

07.Functions
    Functions with & without arguments, keyword arguments
    Functions with Different return types and unpacking
    Functions with with Default arguments
    variadic functions : variable arguments and variable keyword arguments
    Functions with keyword only arguments
    Scoping: Global vs Local
        call by reference
        call by value
class18 17th Dec 2024

    Partial Functions
    Anonymous(Lambda) Functions
    Higher order functions: map(), filter(), functool.reduce()
    Recursions and recursions limit
class19 18th Dec 2024

    inner functions
    closures

08.Decorator Design Pattern
    Necessity
    function Decorator
    Practical Examples
    syntactic sugar for decorators
    multiple decorators on same function
    decorators with arguments
    functools - wrap, lru_cache
    class decorator
class20 19th Dec 2024

09.Iterables, Iterators, Generators and co-routines
    Iterables
        different ways of extracting values from iterables
    Iterators
        iter() protocol
        itertools module
class21 20th Dec 2024

    Generators
        yield vs return
        function vs Generator
        Generator pipelining
        Generator Expression
class22 23rd Dec 2024

    Coroutine
        Generator vs Coroutine
        coroutine pipelining


10.Modules
    Basic Modules
        - math, sys, argparse
class24 23rd Dec 2024

        os, shutil, pathlib, 
Next class
    subprocess, getpass
    time related
        - time, datetime, pytz, timeit, calendar
    concurrency
        - Multiprocessing, Multithreading
    others
        - random, collections, atexit, contextlib, base64, turtle, tqdm
    create user-defined module
    creating user-defined package
