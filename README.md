Project 0x02. AirBnB clone - MySQL 💻
📄 In this project we created version 2 of the Airbnb Clone where we will connect with the databases to continue with the advancement of it.
📋 Requirements
Python Scripts
Allowed editors: vi, vim, emacs.
Files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5).
Files must be executable.
The length of your files will be tested using wc.
Python Unit Tests
All your test files should be inside a folder tests.
You have to use the unittest module.
All your test files should be python files (extension: .py).
All your test files and folders should start by test_.
Your file organization in the tests folder should be the same as your project: ex: for models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py.
SQL Scripts
Files will be executed on Ubuntu 20.04 LTS using MySQL 8.0.
Files will be executed with SQLAlchemy version 1.4.x.
All SQL keywords should be in uppercase (SELECT, WHERE…).
The length of your files will be tested using wc.
🎨 Style
Code should use the PEP 8 style (version 2.7.*).
Comments for your SQL file:
$ cat my_script.sql
-- first 3 students in the Batch ID=3
-- because Batch 3 is the best!
SELECT id, name FROM students WHERE batch_id = 3 ORDER BY created_at DESC LIMIT 3;
$
HBNB - The Console
This repository contains the initial stage of a student project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

Repository Contents by Project Task
Tasks	Files	Description
0: Authors/README File	AUTHORS	Project authors
1: Pep8	N/A	All code is pep8 compliant
2: Unit Testing	/tests	All class-defining modules are unittested
3. Make BaseModel	/models/base_model.py	Defines a parent class to be inherited by all model classes
4. Update BaseModel w/ kwargs	/models/base_model.py	Add functionality to recreate an instance of a class from a dictionary representation
5. Create FileStorage class	/models/engine/file_storage.py /models/_ init _.py /models/base_model.py	Defines a class to manage persistent file storage system
6. Console 0.0.1	console.py	Add basic functionality to console program, allowing it to quit, handle empty lines and ^D
7. Console 0.1	console.py	Update the console with methods allowing the user to create, destroy, show, and update stored data
8. Create User class	console.py /models/engine/file_storage.py /models/user.py	Dynamically implements a user class
9. More Classes	/models/user.py /models/place.py /models/city.py /models/amenity.py /models/state.py /models/review.py	Dynamically implements more classes
10. Console 1.0	console.py /models/engine/file_storage.py	Update the console and file storage system to work dynamically with all classes update file storage
