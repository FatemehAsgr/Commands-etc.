# Django 
Checking if we have python installed:

$ python -v 

$ python3 -v 


Installing python:

$ brew install python

$ brew install python3


Creating a virtual environment:

$ cd -- (GO to the main directory)

$ ls (We are in the main path)

$ mkdir Dev (Creating Dev directory if it doesn't exist)

$ cd Dev (Go to Dev directory) [Dev is where we will keep all of the development projects]

$ mkdir trydjango (Creating a directory named trydjango)

$ cd trydjango (Go to trydjango directory)

$ virtualenv -p python3 . (Creating a virtual environment) *****

$ source bin/activate (in mac)   ||   $ .\scripts\activate (in windows) (Activating the virtual environment) [source is used in mac but not in windows]

$ pip install django==2.0.7 (Installing django in the virtual environment) [2.0.7 is a 2018-version, this will be updated later]


***** THERE ARE FOUR WAYS FOR CREATING A VIRTUAL ENVIRONMENT

1. virtualenv NAME (Virtual environment with whatever python's version is)

2. virtualenv NAME -p python3 (Python's version is 3 and we know it)

3. virtualenv NAME -p PATH (the path is obtained by command: which python)

4. mkdir VIRTUALENV_NAME
   cd VIRTUALENV_NAME
   virtualenv . -p python3 (Whatever version of python)


"For reactivating the virtual environment" 

$ cd Dev

$ cd trydiango

$ source bin/activate (in mac)   ||   $ .\scripts\activate (in windows)


"For deactivating a virtual environment"

$ deactivate (while we are in Dev/trydjango and virtual environment is already activated)
