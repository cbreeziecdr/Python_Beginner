# Python_Beginner
Testing out what I have learned thus far in coding in Python
# testing out python code i've learned 
# Use Python version 3.5.1 coding format in below lines of code
# In below code samples, the code statement is followed by the resulting output given in Python Shell Script Interpreter

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

# Identity operators compare the memory locations of two objects.

 x and y

3

 y and x

2

 x or y

2

 y or x

3

 # Python Decision Making Functions

 # If, Else, Nested If Statements

 bat = 30

 if (bat == 30) : print ("the bat is " + str(int(bat)) + "inches long")

the bat is 30inches long

 if (bat == 30) : print ("the bat is " + str(int(bat)) + " inches long")

the bat is 30 inches long

 if (bat == 20) : print ("the bat is " + str(int(bat)) + "inches long")

else:

	print ("wrong bat size, choose another")
	
wrong bat size, choose another

 nme = "Tim"

 # if, elif, else statement example

 # ask user for number value

 x = input("provide an integer value")

provide an integer value 10

 x

' 10'

 y = int(str(x))

 y

10

 if y < 0:

	b = 2

	print ("y is negative")

elif y == 0:

	b = 0

	print ("y is zero")

elif y > 0 and y <= 2:

	b = 1

	print("y is positive and less than 3")

else:

	b = 3

	print("y is positive and above 2")

	
y is positive and above 2

 z = 15 # nested if statements

 if z < 20:

   print ("z is less than 200")

   if z == 15:

      print ("What is 15")

   elif z == 10:

      print ("What is 10")

   elif z == 5:

      print ("What is 5")

elif z < 5:

   print ("z is less than 5")

else:

   print ("Could not find true value")

   
z is less than 200

What is 15

 # learning coding loops

 # while loop exmaple

 counter = 3 # assign counter variable

 while (counter < 10):

	print ("The round is " , counter)

	counter = counter + 1



The round is  3

The round is  4

The round is  5

The round is  6

The round is  7

The round is  8

The round is  9

 counter = 11 # assign counter variable

 while (counter < 10):

	print ("The round is " , counter)

	counter = counter + 1

	
 number = 4

 while number == 4 : # Example of an infinite loop

	# need use CTRL + C to exit program

	name = input("Enter name : ")

	print ("Your name: ", name)

	
Enter name : Tim

Your name:  Tim

Enter name : Tom

Your name:  Tom

Enter name : Ben

Your name:  Ben

Enter name : 

Traceback (most recent call last):

  File "<pyshell#63>", line 3, in <module>

    name = input("Enter name : ")

  File "C:\Users\Programs\Python\Python35-32\lib\idlelib\PyShell.py", line 1386, in readline

    line = self._line_buffer or self.shell.readline()

KeyboardInterrupt

 # while loop with else statement

 t = 10

 rnd = 0

 while rnd <= t:

	print (rnd, "round of ", t)

	rnd = rnd + 1

else:

	print ("game over")

0 round of  10

1 round of  10

2 round of  10

3 round of  10

4 round of  10

5 round of  10

6 round of  10

7 round of  10

8 round of  10

9 round of  10

10 round of  10

game over

 # for loop examples

 for digit in '12345': # 1st example

	print ('Current digit :', digit)

	
Current digit : 1

Current digit : 2

Current digit : 3

Current digit : 4

Current digit : 5

>> for state in states: #  2nd example using for loop and tuple variable

	print ("State code :", state)

	
State code : MA

State code : TX

State code : NY

State code : CA

 for index in range(len(states)): #  3nd ex for loop and tuple variable

	print ("State code :", states[index])
	

State code : MA

State code : TX

State code : NY

State code : CA

 # len() built-in function gives total number of elements in tuple

 # range() built-in function provides the sequence to iterate over

 k = 2

 l = 3

 m = 4

 # nested loops

 c = 3

 j = 10

 while(c <= 3):

	while(j <= 13):

		if c/j is not 0 : break

		j = j + 1
	if ( c + j <=16): print ("keep moving")

	c = c + 1


keep moving

 print("hello") #break statements

hello

 # break statement stops execution of current loop and resumes execution \

 # at the next statement

 for digit in 'United': # break statement stops loop at letter e

	if digit == 'e':

		break

	print ('Next digit :', digit)


Next digit : U

Next digit : n

Next digit : i

Next digit : t

 team = 5

 while team < 10:

	print ('Team number :', team)

	team = team + 1

	if team == 9:

		break
	
Team number : 5

Team number : 6

Team number : 7

Team number : 8

 # continue statement: loop skip remainder of body and immediately retest

 # condition prior to reiterating

 # useable in both while and for loops

 for word in 'cannot': # ex of continue statement in for loop

	if word == 'n':

		continue

	print ('Letter is : ', word )
	
Letter is :  c

Letter is :  a

Letter is :  o

Letter is :  t

 ty = 100 # continue statement in while loop

 while ty > 90:

	ty = ty - 2

	if ty ==92:

		continue

	print ('There are ', ty, 'seconds left')

	
There are  98 seconds left

There are  96 seconds left

There are  94 seconds left

There are  90 seconds left

 for ltr in 'Dumpster':

	if ltr == 's':

		pass

		print ('between 1st and 2nd syllable')

	print ('Current letter is :', ltr)
	

Current letter is : D

Current letter is : u

Current letter is : m

Current letter is : p

between 1st and 2nd syllable

Current letter is : s

Current letter is : t

Current letter is : e

Current letter is : r

 x = -2.5464

 y = abs(x)

 y

2.5464

 y = abs(x) # absolute value
 
 math.ceil(x) # the ceiling of x

-2

 a = 2

 b = 3

 c = 4

 e = 2

 x = 1
 y = 2

 import math

 math.exp( x )

2.718281828459045

 import math

 z = 1.5

 math.floor( z )

1
 
 math.log(1.5)

0.4054651081081644

 import math

 math.log10(1.5)

0.17609125905568124

 import math

 max(2, 3, 5)

5

 min(10, 43, 34, 7)

7

 import math

 math.modf(12.343)

(0.34299999999999997, 12.0)


 import math

 math.pow(2,3)

8.0

 import math
  
print ("round(80.23456, 2) : ", round(80.23456, 2))

round(80.23456, 2) :  80.23

 round(12.239120,2)

12.24

 import math

 math.sqrt(64)

8.0

import random

 print ("choice(['MA, BA, TX, MT, CA']) : ", random.choice(['MA, BA, TX, MT, CA']))

choice(['MA, BA, TX, MT, CA']) :  MA, BA, TX, MT, CA

 print ("choice(['MA', 'BA', 'TX', 'MT', 'CA']) : ", random.choice(['MA', 'BA', 'TX', 'MT', 'CA']))

choice(['MA', 'BA', 'TX', 'MT', 'CA']) :  CA

 import random

# Select an even number in 20 <= number < 352

# Select an even number in 20 <= number < 352

print ("randrange(20, 352, 2) : ", random.randrange(20, 352, 2))

randrange(20, 352, 2) :  208

 # Select an even number in 20 <= number < 352

print ("randrange(20, 352, 2) : ", random.randrange(20, 352, 2))

randrange(20, 352, 2) :  40

 import random

# 1st random number

print ("random() : ", random.random() )

random() :  0.8079796235628943

# random number

print ("random() : ", random.random() )

random() :  0.017438165530229366


 import random

 random.random()

0.6523036668102292

 random.random()

0.03360773551597296

# print out same random number repeatly

 import random

 random.seed(10)

 print ("Random number with seed 10:", random.random())

Random number with seed 10: 0.5714025946899135

 print ("Random number with seed 10:", random.random())

Random number with seed 10: 0.4288890546751146

 random.seed(10)

 print ("Random number with seed 10:", random.random())

Random number with seed 10: 0.5714025946899135

 random.seed(10)

 print ("Random number with seed 10:", random.random())

Random number with seed 10: 0.5714025946899135

# to get same random number, need to put random.seed(#) statement

# right before the random.random() statement

# begin all these statements first with a improt random statement

 import random

 a_list = [15, 17, 5, 9] # list variable

 random.shuffle(a_list) # randomize items in list in place

 print ("reshuffled list:", a_list)

reshuffled list: [5, 15, 17, 9]

 import random

 print("random float number between parameters x, y :", random.uniform(5,10))

random float number between parameters x, y : 6.030491160697508

# trigonometric functions

asin(0.45) :  0.4667653390472964

import math

print ("atan(0) : ",  math.atan(0)) # returns arc tangent of x, in radians

atan(0) :  0.0

import math

print ("atan2(-0.1,-0.1) : ",  math.atan2(-0.1,-0.1))

atan2(-0.1,-0.1) :  -2.356194490192345

# above returns atan(y / x), in radians

import math

print ("cos(-3) : ",  math.cos(-3)) # returns the cosine of x radians

cos(-3) :  -0.9899924966004454

import math

print ("hypot(1, 4) : ",  math.hypot(1, 4))

hypot(1, 4) :  4.123105625617661

# return the Euclidean norm, sqrt(x*x + y*y)

import math

print ("sin(5) : ",  math.sin(5)) # returns the sine of x, in radians

sin(5) :  -0.9589242746631385

import math

print ("tan(4) : ",  math.tan(4)) # returns the tangent of x radians

tan(4) :  1.1578212823495775

import math

print ("degrees(5) : ",  math.degrees(5))

degrees(5) :  286.4788975654116

# converts angle x from radians to degrees

import math

print ("radians(286.4788975654116) : ",  math.radians(286.4788975654116))

radians(286.4788975654116) :  5.0

# radians() converts angle x from degrees to radians

# String variables

t_1 = "Olah"

t_1

'Olah'

# can "update" an existing string by reassigning variable

t_2 = t_1[:4] + "Amigo"

t_2

'OlahAmigo'

t_3 = t_1[:5] + "Amigo"

t_3

'OlahAmigo'

t_4 = t_1[:5] + " Amigo"

t_4

print ("\a")

print("\b")
 
print("\cx")

\cx

print("C-x")

C-x

print("\e")

\e

print("\f")
 
print ("\a") # bell or alert

print("\b") # backspace
 
print("\cx") # Control-x

\cx

print("C-x") # Control-x

C-x

print("\e") # Escape

\e

print("\f") # Formfeed
 
print("M-\C-x") # Meta-Control-x

M-\C-x

print("\n") # Newline

print("\nnn") # Octal notation, where n is in the range 0.7

nn

print ("\r") # Carriage return

print ("\s") # Space

\s

print ("\t") # Tab
	
print ("\v") # Vertical tab


# String Special Operators

a = "Tell"

b = "Sam"

d, e = "Bye", "Ted"

a

'Tell'

b

'Sam'

d

'Bye'

e

'Ted'

f = a + b

f

'TellSam'

f = a + b # Concatenation - Adds values on either side of the operator

0f

'TellSam'

a * 3 # Repetition

'TellTellTell'

a[1:] # Slice - Gives the character from the given index

'ell'

a[1] # Slice - Gives the character from the given index

'e'

a[2:4] # Range Slice - Gives the characters from the given range

'll'

"l" in a # membership

True

"b" not in "Tell" # Membership - Returns true if a character does not exist in the given string

True

print (r"Bye") # Raw String - Suppresses actual meaning of Escape characters.

Bye

print("\n") # Newline

print("\n hi ") # Newline

 hi 

print(r"\n hi ") # Newline

\n hi 

# String formatting operator

"%" # 	Format - Performs String formatting

'%'

print ("My name is %s and weight is %d kg!" % ('Zara', 21))

My name is Zara and weight is 21 kg!


int(25)

25

# %c  	character

# %s string conversion via str() prior to formatting

# %i signed decimal integer

# %d  	signed decimal integer

# %u unsigned decimal integer

# %o octal integer

# %x hexadecimal integer (lowercase letters)

# %X hexadecimal integer (UPPERcase letters)

# %e  	exponential notation (with lowercase 'e')

# %E  	exponential notation (with UPPERcase 'E')

# %f  	floating point real number

# %g  	the shorter of %f and %e

# %G  	the shorter of %f and %E

# * 	argument specifies width or precision

# - 	left justification

# + display the sign

# <sp> leave a blank space before a positive number

# # 	add the octal leading zero ( '0' ) or hexadecimal leading \ '0x' or '0X', depending on whether 'x' or 'X' were used.

# 0 pad from left with zeros (instead of spaces)

# % 	'%%' leaves you with a single literal '%'

# (var) mapping variable (dictionary arguments)

# m.n. 	m is the minimum total width and n is the number \ of digits to display after the decimal point (if appl.)

# Triple Quotes - allowing strings to span multiple lines, \including verbatim NEWLINEs, TABs, and any other special characters

# example ]

story = '''The writing on the wall was really lengthy. There will be more I can add to the story here. The castle lefted the stature of the kindom to newer heights'''

story

'The writing on the wall was really lengthy. There will be more I can add to the story here. The castle lefted the stature of the kindom to newer heights'

"example of having tabs \t in text like here, a new line \n like this"

'example of having tabs \t in text like here, a new line \n like this'

ab = "example of having tabs \t in text like here, a new line \n like this"

ab

'example of having tabs \t in text like here, a new line \n like this'

print("example of having tabs \t in text like here, a new line \n like")

example of having tabs 	 in text like here, a new line 

 like

print ('C:\\nowhere')

C:\nowhere

print (r'C:\\nowhere')

C:\\nowhere

# Raw strings do not treat the backslash as a special character at all.

# Every character you put into a raw string stays the way you wrote i

#

#

# Unicode String

# Normal strings are store in 8-bit ASCII

# Unicode strings are store in 16-bit Unicode

# Unicode allows a more varied set of characters

# Unicode allows inclusion of special characters from most world languages

print (u'Hello, world!')

Hello, world!

print (r'Hello, world!')

Hello, world!

print(u'Ça va bien')

Ça va bien

print(u'Bibliothèque au Paris') # Unicode examples

Bibliothèque au Paris

print('Bibliothèque au Paris')

Bibliothèque au Paris

#

#

# Built-in String Methods

# Python includes the following built-in methods to manipulate strings

str.capitalize('thomas') # capitalizes first letter of string

'Thomas'

var = "texas"

var.center(8, 'b') # centers string variable

'btexasbb'

var.center(8, ' ') # centers string variable with fill char being a space

' texas  '

# method count()

# returns the number of occurrences of substring sub in the range [start

# , end]. Optional arguments start and end are interpreted

# as in slice notation.

# str.count(sub, start= 0,end=len(string))

# in above str is the variable in which string is stored

str = "This is Mississippi isn't it";

sub = "s" # going to get count of existence of letter 's' in string

print ("str.count(sub, 1,20) : ", str.count(sub, 1,20))

str.count(sub, 1,20) :  6

# above output says there was 6 instances of letter 's' in string str

# method decode() decodes the string using the codec registered

# for encoding. It defaults to the default string encoding.

# Str.decode(encoding='UTF-8',errors='strict')

# str is variable in which string is stored

str = "Good morning Miami!"

# endswith() Method

# It returns True if the string ends with the specified suffix, otherwise return False optionally restricting the matching with the given indices start and end.

# str.endswith(suffix[, start[, end]])

# TRUE if the string ends with the specified suffix, otherwise FALSE.

str = "What will the end be?";

suffix = "be?";

print (str.endswith(suffix)) # checks if string ends with suffix given

True

suffix_1 = "start"

print (str.endswith(suffix_1)) # checks if string ends with suffix given

False

print (str.endswith(suffix, 5, 30)) # if string range ends with suffix

True

# String expandtabs() Method

# str.expandtabs(tabsize=8)

# It returns a copy of the string in which tab characters ie. '\t' are expanded using spaces, optionally using the given tabsize (default 8)..

###

str = "this is\tstring example....wow!!!";

print ("string before:" + str)

string before:this is	string example....wow!!!

print ("string after:" + str.expandtabs())

string after:this is string example....wow!!!

print ("string after double expanded tab:" + str.expandtabs(16))

string after double expanded tab:this is         string example....wow!!!

#####

#####

# String find() Method

# It determines if string str occurs in string, or in a substring of string if starting index beg and ending index end are 
given.

# str.find(str, beg=0 end=len(string))

# str -- This specifies the string to be searched

# beg -- This is the starting index, by default its 0.

# end -- This is the ending index, by default its equal to the lenght of the string.

str1 = "move to the left and the right" # full string

str2 = "left" # substring to find

print (str1.find(str2))

12

# Return value of String find() method is Index if found and -1 otherwise.

print(str1.find(str2,25, 40)) # range find example

-1

# above return of -1 means substring was not found in string w/in range

#

# String index() Method

#####

# It determines if string str occurs in string or in a substring of string if starting index beg and ending index end are 
given. This method is same as find(), but raises an exception if sub is not found.

#

# str.index(str, beg=0 end=len(string))

str1 = "move to the left and the right" # full string

str2 = "left" # substring to find

print (str1.index(str2)) # the position of substring in full string

12

print (str1.index(str2, 3, 20)) # the position of substring in full string

12

#####

#####

#####

# String isalnum() Method

# The method isalnum() checks whether the string consists of alphanumeric characters.

# str.isa1num()

# This method returns true if all characters in the string are alphanumeric and there is at least one character, false 
otherwise.

str = "win2016";  # No space in this string

print (str.isalnum()) # example

True

str = "win 2016";

print (str.isalnum()) # example

False

# String isalpha() Method

str = "hello";  # No space & digit in this string

print (str.isalpha())

True

#String isdigit() Method

# The method isdigit() checks whether the string consists of digits only.

str = "1738";  # Only digit in this string

print (str.isdigit())

True

# String islower() Method

# The method islower() checks whether all the case-based characters (letters) of the string are lowercase.

str = "THIS is string example....wow!!!";

print (str.islower())

False

# String isnumeric() Method

# The method isnumeric() checks whether the string consists of only numeric characters. This method is present only on 
unicode objects.

# To define a string as Unicode, one simply prefixes a 'u' to the opening quotation mark of the assignment. Below is the 
example

str = u"this2009";

print (str.isnumeric())

False

# String isspace() Method

# The method isspace() checks whether the string consists of whitespace.
