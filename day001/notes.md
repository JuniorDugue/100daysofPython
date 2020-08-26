# Notes


<!-- notes -->
don't name files 'datetime.py' because we're using the datetime module

python extensions end with .py

***

## python in the shell
- to run python in terminal `python3`
- you know you're in the python shell by seeing the 3 arrows `>>>`

- first run `python3`
then import the module via `import datetime`
then execute `datetime.datetime.now()` to display the time

***

## python in its file
- if you're in python's shell, ctrl+c won't exit, to exit use `exit()` in the terminal 

- to execute the python files, `python3 nameoffile.py` in our case `python3 basics.py`

***

## to print

- import datetime
  
  print(datetime.datetime.now())

  then via terminal `python3 filename.py`


***

## to combine the string 'the date and time is' + datetime
- import datetime
  
  print("The date and time is")

  print (datetime.datetime.now())

that'll be seperated in the terminal so to have them on one line write instead

- import datetime
  
  print("The date and time is", datetime.datetime.now())
***