pi = 3.14
print(type(pi))- show the type of the varriable
-----------------------------------------------------
a, b, c = 1, 2, 3
print(a, b, c)
-----------------------------------------------------
x = [1, 2, [3, 4, 5], 6, 7] # this is nested list
print x[2]
# Output: [3, 4, 5]
print x[2][1]
# Output: 4
-----------------------------------------------------
def my_function(): # This is a function definition. Note the colon (:)
a = 2 # This line belongs to the function because it's indented
return a # This line also belongs to the same function
print(my_function()) # This line is OUTSIDE the function block
-----------------------------------------------------
if a > b: # If block starts here
print(a) # This is part of the if block
else: # else must be at the same level as if
print(b) # This line is part of the else block
-----------------------------------------------------
x or y # if x is False then y otherwise x
x and y # if x is False then x otherwise y
not x # if x is True then False, otherwise True
-----------------------------------------------------
issubclass(bool, int) # True
isinstance(True, bool) # True
isinstance(False, bool) # True
-----------------------------------------------------
True + False == 1 # 1 + 0 == 1
True * True == 1 # 1 * 1 == 1
-----------------------------------------------------
int_list = [1, 2, 3]
string_list = ['abc', 'defghi']
empty_list = []
mixed_list = [1, 'abc', True, 2.34, None]
nested_list = [['a', 'b', 'c'], [1, 2, 3]]
-----------------------------------------------------
names = ['Alice', 'Bob', 'Craig', 'Diana', 'Eric']
print(names[0]) # Alice
print(names[2]) # Craig
print(names[-1]) # Eric
print(names[-4]) # Bob
names[0] = 'Ann'
print(names) #Outputs ['Ann', 'Bob', 'Craig', 'Diana', 'Eric']
-----------------------------------------------------
names = ['Alice', 'Bob', 'Craig', 'Diana', 'Eric']
names.append("Sia")
print(names)
# Outputs ['Alice', 'Bob', 'Craig', 'Diana', 'Eric', 'Sia']
-----------------------------------------------------
names.insert(1, "Nikki")
print(names)
# Outputs ['Alice', 'Nikki', 'Bob', 'Craig', 'Diana', 'Eric', 'Sia']
-----------------------------------------------------
names.remove("Bob")
print(names) # Outputs ['Alice', 'Nikki', 'Craig', 'Diana', 'Eric', 'Sia']
-----------------------------------------------------
names.pop() # Outputs 'Sia'
-----------------------------------------------------
name.index("Alice")
0
-----------------------------------------------------
len(names)
6
-----------------------------------------------------
a = [1, 1, 1, 2, 3, 4]
a.count(1)
3
-----------------------------------------------------
a.reverse()
[4, 3, 2, 1, 1, 1]
# or
a[::-1]
[4, 3, 2, 1, 1, 1]
-----------------------------------------------------
ip_address = ('10.20.30.40', 8080)
list which doesnt change
-----------------------------------------------------
from collections import defaultdict
state_capitals = {
 'Arkansas': 'Little Rock',
 'Colorado': 'Denver',
 'California': 'Sacramento',
 'Georgia': 'Atlanta'
}
state_capitals = defaultdict(lambda: 'it doesnt exist')
ca_capital = state_capitals['California']
-----------------------------------------------------
pow(2,3) #8
-----------------------------------------------------
import math
dir(math)  #show all the commands
-----------------------------------------------------
for function page U have to open a new python file in the
same folder.
you type "import fileName" at the top of the page
and U call for the function with "nameOfTheFile.nameOfTheFunction()"
-----------------------------------------------------
import datetime
today = datetime.datetime.now()
str(today) # Output: '2016-09-15 06:58:46.915000'
repr(today) # Output: 'datetime.datetime(2016, 9, 15, 6, 58, 46, 915000)'
-----------------------------------------------------
b = frozenset('asdfagsa')
print(b)
> frozenset({'f', 'g', 'd', 'a', 's'})
-----------------------------------------------------
tuple = (123,'hello')
print(tuple) #will output whole tuple. (123,'hello')
print(tuple[0]) #will output first value. (123)
-----------------------------------------------------
לחזור לעמוד 60
-----------------------------------------------------
