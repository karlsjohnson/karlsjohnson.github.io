# Python


## Basic
* Control-C to exit
* Structure
* Each line has a command, before a NEWLINE.
* Some computer languages have a ; at the end of the command, python does not.
* Tabs and spaces do matter in python, be careful how they are used.
* A # is used to add a comment
* placement spaces matters (Tabs)
* conditions ==, !=, >, <, >=, <=
* When a data’s value can be changed it is called
* Variables are used to store data
* Operations
* Operations can be used with most variables including strings
* Basic math operators include: +, -, \*, /
* Everything is an object or data
* When the type is set, it can not be changed
* All data in a Python program is represented by objects or by relations between objects.
* No need to set variable type
* Comments
- [Python](#python)
	- [Basic](#basic)
	- [Variables](#variables)
	- [Strings](#strings)
	- [tuples](#tuples)
- [Common Commands](#common-commands)
	- [If statements](#if-statements)
	- [for statements](#for-statements)
	- [while statements](#while-statements)

## Variables

```Python
New = ['one','two','three','four']
print(New[2])
print(New[2:5])
New.append('five')
del New[2] #delete three
list3 = list1 + list2 # Combine lists
t=12+23 spaces = ' ' * 25
```

## Strings

* adding a %s allows programmer to add data to string later
* Some words are reserved

```Python
number of coins=200
fred = 'What isn't the "variable?"'
wizard = ['spider','jump bug','fly']
wizard[0] = 'ant'
 message = 'I scored %s points' points = 1000 print (message % points)
```

* Embedding values in a string
	* ' or " are used to string or text        
	* Names can not have spaces        
	* \ are used to add special characters that are normally used for code        
	* Used for \, ", ', \n (return)        
	* = is used to set the variable        
	* List can store other lists        
	* Data Types        
	* Sequences - a[i] or a[one, two, three]        
	* None - no value boolean is false        
	* Integers(int) - a number with no decimal        
	* Real (float) - a number with a decimal`        
	* Booleans - False or True        
	* string “String” in quotes

## tuples

* read only list
* fibs = (0,1,2,3)        
* Maps (List with key and value, dictionary)        
* fav sports = { 'Ralph' : 'Football' , 'Joe' : 'Baseball' , 'Mike' : 'Basketball' }        
* fav sports['Ralph'] = 'Soccer'        


# Common Commands
 
```Python        
print ('variable')        
print to Terminal        
print ("String")
```

## If statements

```Python
if age > 20:
print('you are old')
elif age == 30 or age == 31
print('30 or 31')
else
print('unkown')
```

## for statements

```Python
for x in range(0,5): print('hello %s' % x)
```

* Convert string to number        
```python
string = str(number)        
float = float(string)        
number = int(string)        
```

## while statements

* Variables do not need to be defined        
* Try statements        
* Setup a system the runs until you want it to stop (ctrl-C)        
```python
while x < 50 and y < 100: x = x +1 while True code if x == True break                        
while True: try:
'code you want to run continuously '
except KeyboardInterrupt:
'code you want to run at end, after you press ctrl-c'
break #breaks out of while loop
```
