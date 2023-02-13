AirBnB Clone
The Airbnb clone is a fully-fledged web application that integrates database storage, back-end API, and front-end interface to create a replication of the AirBnB platform. At present, the project has solely implemented the back-end console.

[![NPM Version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Downloads Stats][npm-downloads]][npm-url]

AirBnB Clone - The Console



Console
The console is a command line interpreter that permits management of the backend of AirBnB. It can be used to handle and manipulate all classes utilized by the application (achieved by calls on the storage object defined above).

Using the Console:

The AirBnB console can be run both interactively and non-interactively. To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line.

$ echo "help" | ./console.py
(hbnb) 
Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb) 
$
Alternatively, to use the AirBnB console in interactive mode, run the file console.py by itself:

$ ./console.py
While running in interactive mode, the console displays a prompt for input:

$ ./console.py
(hbnb) 
To quit the console, enter the command quit, or input an EOF signal (ctrl-D).

$ ./console.py
(hbnb) quit
$
Console Commands
The AirBnB console supports the following commands:

create Usage: create Creates a new instance of a given class. The class' ID is printed and the instance is saved to the file file.json.

show Usage: show or .show() Prints the string representation of a class instance based on a given id..

$ ./console.py
(hbnb) create User
(hbnb)
(hbnb) show User uid		
(hbnb) 
(hbnb) User.show(uid)
(hbnb) 
$
Meta
Jamal mteri –jamalmteri@gamil.com

Distributed under the XYZ license. See LICENSE for more information.

https://github.com/jamalmteri
