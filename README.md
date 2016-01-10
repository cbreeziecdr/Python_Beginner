# Python_Beginner
Testing out what I have learned thus far in coding in Python
# testing out python code i've learned 
 # testing out python code i've learned 
 # print function

 a = 2

 print (a)
2

 b = '2'

 print (b)
2

 c = 'hello'

 d = a + int(str(b))

 print(d)
4

 print(a * 2)
4

 e = 'hello'

 print (e * 3) # string variable multiplication, print function
hellohellohello

# Tuples and List variables

 tuple = ('abc', 2, 'hi') # tuple, is read only

 list = ['cde', 20, 'bye'] # list, supports item assignment

 list[2] = 30 # item reassignment, changing 3 key in list from 20 to 30

 print(list) # new list after reassignment

['cde', 20, 30]

list = [ 'abcd', 786, 2.23, 'john', 70.2 ] # list variable

 list # call list variable called 'list'

['abcd', 786, 2.23, 'john', 70.2]

 b = [ '2', 24, 'born']  # list variable called 'b'

 b # call list variable called 'b'

['2', 24, 'born']

 print (list + b ) print lists 'list' and 'b' together

['abcd', 786, 2.23, 'john', 70.2, '2', 24, 'born']

 print (list[0]) # print first item in list variable 

abcd

 print(list[2]) # print third item in list variable 

2.23

 print(list[2:]) # print from third item in list variable 

[2.23, 'john', 70.2]

 tuple = ( 'abcd', 786, 2.23, 'john', 70.2) # tuple variable

 tinytuple = (123, 'john') # tuple variable

 tuple # call tuple variable called 'tuple'

('abcd', 786, 2.23, 'john', 70.2)

 tinytuple # call tuple variable called 'tinytuple'

(123, 'john')

 print(tuple[0]) # print first item in tuple variable 

abcd

 print(tuple[1:3]) # print 2nd to 4th items in tuple variable 

(786, 2.23)

 print(tuple[2:]) # print 3rd item in tuple variable 

(2.23, 'john', 70.2)

 print(tinytuple * 2) # print tuple variable 'x' times

(123, 'john', 123, 'john') 

 print(tuple + tinytuple) # print tuple variables together

('abcd', 786, 2.23, 'john', 70.2, 123, 'john')

 tuple[2] = 1000 # invalid syntax with tuple

Traceback (most recent call last):
  File "<pyshell#73>", line 1, in <module>
    tuple[2] = 1000 # invalid syntax with tuple
TypeError: 'tuple' object does not support item assignment

 list[1] = 1000 # try it

 list

['abcd', 1000, 2.23, 'john', 70.2]

 a = b = c = 2 # assginment of multiple variables to same value in \ same assignment expression

 a

2

 b

2

 c

2

 print c 

SyntaxError: Missing parentheses in call to 'print'

 print (c) # learning from mistakes, how punctuation is key

2

 a,b,c=1,2,"john" # multilple variable assignments in one line

 a

1

 b

2

 c

'john'

 del c # deleting a variable 

 c # trying to call a deleted variable

Traceback (most recent call last):
  File "<pyshell#14>", line 1, in <module>
    c
NameError: name 'c' is not defined

 del a # deleting a variable

 a # trying to call a deleted variable

Traceback (most recent call last):
  File "<pyshell#16>", line 1, in <module>

# Integer, Floating, String, representation, evaluatem, hexideciminal, octagonal Variables

 n = 20

 int(n) # making variable n into an ingteger variable

20

 float(int(n)) # making variable n into a floating variable

20.0

 str = 'Hello World!' # variable assignment

 print (str) # print variable

Hello World!

 print (str[0]) # print first letter or digit of variable

H

 print (str[2:]) # print from 3 letter or digit of variable

llo World!

 print (str * 2) # print variable multiple times, 2 times

Hello World!Hello World!

 print (str + "TEST")

Hello World!TEST

int(t) # integer variable

2

 repr(t) # representation variable

"'2'"

 eval(t) # evaluate variable

2

 cd = 2

 chr(cd) # character variable

'\x02'

 hex(m) # hexideciminal variable

'0xc'

 oct(m) # octagonal variable

'0o14'


# Dictionary variables where given definitions for each item and store these assignments into one dictionary variable 

 dict = {} # make 'dict' variable a dictionary variable

 dict # call dictionary variable called 'dict'

{}

 dict['one'] = "This is one" # assign 'one' a value in dictionary

 dict

{'one': 'This is one'}

 dict[2] = "This is two" # assign '2' a value in dictionary

 dict

{2: 'This is two', 'one': 'This is one'}

 print (dict['one']) # Prints value for 'one' key

This is one

 print (dict[2])

This is two

 tinydict = {'name': 'john', 'code':6734, 'dept': 'sales'} # assign items to definitions in dictionary variable

 tinydict

{'name': 'john', 'dept': 'sales', 'code': 6734}

 print (tinydict.keys()) # prints the keys in dictionary variable called 'tinydict'

dict_keys(['name', 'dept', 'code'])

 print (tinydict.values()) # Prints all the values

dict_values(['john', 'sales', 6734])

 t = '2'

 # membership operators
 list_a = (1, 2, 10, 15)

 list_a

(1, 2, 10, 15)

 2 in list_a

True

 3 in list_a

False

 13 not in list_a

True

 10 not in list_a

False

 # indentity operators
 # identity operators

 x = 2

 y = 3

 x is y

False

 z= 2

 x is z

True

 x is not y

True

 # identity operators
 # Identity operators compare the memory locations of two objects.

 x and y

3

 y and x

2

 x or y

2

 y or x

3
