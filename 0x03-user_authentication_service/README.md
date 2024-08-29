# User authentication service
This project will teach us how to implement the user authentication service. It is part of the backend specialization at ALX.

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* How to declare API routes in a Flask app
* How to get and set cookies
* How to retrieve request form data
* How to return various HTTP status codes

## Requirements
* All files are interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
* All files end with a new line
* The first line of all files is exactly `#!/usr/bin/env python3`
* There is a `README.md` file, at the root of the folder of the project
* All code used the `pycodestyle` style (version 2.5)
* You should use `SQLAlchemy` 1.3.x
* All files are executable
* The length of all files are tested using `wc`
* All modules have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All classes have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All functions (inside and outside a class) have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
* All functions and coroutines are type-annotated.
* The flask app should only interact with Auth and never with DB directly.
* Only public methods of Auth and DB should be used outside these classes.
