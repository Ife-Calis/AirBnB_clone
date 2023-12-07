# 0x00. AirBnB clone - The console
  `Group project` `Python` `OOP`
```
 By: Guillaume
 Weight: 5
 Project to be done in teams of 2 people (your team: Ifechukwu Anyika, Chioma Iwuoha)
 Project will start Dec 4, 2023 7:00 AM, must end by Dec 11, 2023 7:00 AM
 Checker will be released at Dec 9, 2023 1:00 PM
 Manual QA review must be done (request it when you are done with the project)
 An auto review will be launched at the deadline
```
#### Concepts
For this project, we expect you to look at these concepts:

* __Python packages__
* __AirBnB clone__


## Background Context
### Welcome to the AirBnB clone project!
Before starting, please read the __AirBnB__ concept page.

#### First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the __AirBnB clone__. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

* put in place a parent class (called `BaseModel`) to take care of the initialization, serialization and deserialization of your future instances
* create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
* create all classes used for AirBnB (`User`, `State`, `City`, `Place`…) that inherit from `BaseModel`
* create the first abstracted storage engine of the project: File storage.
* create all unittests to validate all our classes and storage engine
### What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc…
* Do operations on objects (count, compute stats, etc…)
* Update attributes of an object
* Destroy an object
## Resources
#### Read or watch:

* cmd module
* cmd module in depth
* __packages__ concept page
* uuid module
* datetime
* unittest module
* args/kwargs
* Python test cheatsheet
* cmd module wiki page
* python unittest
## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, __without the help of Google__:

## General
* How to create a Python package
* How to create a command interpreter in Python using the `cmd` module
* What is Unit testing and how to implement it in a large project
* How to serialize and deserialize a Class
* How to write and read a JSON file
* How to manage `datetime`
* What is an `UUID`
* What is `*args` and how to use it
* What is `**kwargs` and how to use it
* How to handle named arguments in a function
## Copyright - Plagiarism
* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.
## Requirements
### Python Scripts
* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All your files should end with a new line
* The first line of all your files should be exactly `#!/usr/bin/python3`
* A `README.md` file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle (version `2.8.*`)
* All your files must be executable
* The length of your files will be tested using `wc`
* All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
### Python Unit Tests
* Allowed editors: `vi`, `vim`, `emacs`
* All your files should end with a new line
* All your test files should be inside a folder `tests`
* You have to use the `unittest module`
* All your test files should be python files (extension: `.py`)
* All your test files and folders should start by `test_`
* Your file organization in the tests folder should be the same as your project
* e.g., For `models/base_model.py`, unit tests must be in: `tests/test_models/test_base_model.py`
* e.g., For `models/user.py`, unit tests must be in: `tests/test_models/test_user.py`
* All your tests should be executed by using this command: `python3 -m unittest discover tests`
* You can also test file by file by using this command: `python3 -m unittest tests/test_models/test_base_model.py`
* All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
* We strongly encourage you to work together on test cases, so that you don’t miss any edge case
### GitHub
__There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score__.

## More Info
#### Execution
Your shell should work like this in interactive mode:
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```
But also in non-interactive mode: (like the Shell project in C)
```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```
All tests should also pass in non-interactive mode: `$ echo "python3 -m unittest discover tests" | bash`

## Purpose To build a website similiar to AirBnB with HTML/CSS:
* Learn the basics of HTML and css
* Get familiar with syntax of both languages
* Understand basic mobile responsive designs

## How do I start it?
* open any index.html documents. I suggest trying highest number.html

## USAGE
* hover pointer over locations and amenities to test dropdown
* hover pointer over list of dropdown to check if items is highlighted and darker
* hover pointer over to each place card to check if other cards will response by lowering opacity
* check if cards will expand when in larger screen
* hover pointer to each card AFTER reducing viewport/screen to mobile size, to see the cards will NOT expand

## Responsive Elements
* media queries for 3 breakpoints
* transform for expand disabled when smaller
* cards will align to single columns

## Validation
* All HTML/CSS files is validated using w3c_validator located in the same directory that check fors syntax or nesting errors

```bash
# Repo hierarchy
├── AIRBNB
├── AUTHORS
├── console.py
├── models
│   ├── amenity.py
│   ├── base_model.py
│   ├── city.py
│   ├── engine
│   │   ├── file_storage.py
│   │   └── __init__.py
│   ├── __init__.py
│   ├── place.py
│   ├── review.py
│   ├── state.py
│   └── user.py
├── README.md
├── tests
│   ├── __init__.py
│   └── test_models
│       ├── __init__.py
│       ├── test_amenity.py
│       ├── test_base_model.py
│       ├── test_city.py
│       ├── test_engine
│       │   ├── __init__.py
│       │   └── test_file_storage.py
│       ├── test_place.py
│       ├── test_review.py
│       ├── test_state.py
│       └── test_user.py
└── web_static
    ├── 0-index.html
    ├── 1-index.html
    ├── 2-index.html
    ├── 3-index.html
    ├── 4-index.html
    ├── 5-index.html
    ├── 6-index.html
    ├── 7-index.html
    ├── 8-index.html
    ├── images
    │   ├── icon.png
    │   └── logo.png
    ├── styles
    │   ├── 2-common.css
    │   ├── 2-footer.css
    │   ├── 2-header.css
    │   ├── 3-common.css
    │   ├── 3-footer.css
    │   ├── 3-header.css
    │   ├── 4-common.css
    │   ├── 4-filters.css
    │   ├── 5-filters.css
    │   ├── 6-filters.css
    │   ├── 7-filters.css
    │   ├── 7-places.css
    │   └── test.css
    └── w3c_validator.py

8 directories, 50 files
```
# Authors
Ifechukwu Anyika||Chioma Iwuoha
