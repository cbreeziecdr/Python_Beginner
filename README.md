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

# Built-in String Methods

####

# String istitle() Method

# The method istitle() checks whether all the case-based characters in the string following non-casebased letters are 
uppercase and all other case-based characters are lowercase.

# str.istitle()

# This method returns true if the string is a titlecased string and there is at least one character, for example uppercase characters may only follow uncased characters and lowercase characters only cased ones.It returns false otherwise.

str = "The University of Greatness";

print (str.istitle())

False

str2 = "The university of greatness";

print (str2.istitle())

False

str = "The University Of Greatness";

print (str.istitle())

True

# String isupper() Method

# The method isupper() checks whether all the case-based characters (letters) of the string are uppercase.

# str.isupper()

# This method returns true if all cased characters in the string are uppercase and there is at least one cased character, 
false otherwise.

str = "THIS IS STRING EXAMPLE....WOW!!!";

print (str.isupper())

True

var = "Upper downer flat"

print (var.isupper())

False

# String join() Method

# The method join() returns a string in which the string elements of sequence have been joined by str separator.

# str.join(sequence)

# This method returns a string, which is the concatenation of the strings in the sequence seq. The separator between elements is the string providing this method.

slash = "/"

seq = ("01","16","2016") # this the sequence of strings

print (slash.join( seq )) # joins the sequence of strings with slashes

01/16/2016

empty = ""

seq = ("01","16","2016") # this the sequence of strings

print (empty.join( seq )) # joins the sequence of strings with emptiness

01162016

# String len() Method

# The method len() returns the length of the string.

# len( str )

string = "how many characters are in this sentence";

print ("there are ", len(string), "characters in string")

there are  40 characters in string

# String ljust() Method

# The method ljust() returns the string left justified in a string of length width. Padding is done using the specified 
fillchar (default is a space). The original string is returned if width is less than len(s).

# str.ljust(width[, fillchar])

# width -- This is string length in total after padding

# fillchar -- This is filler character, default is a space.

str = " To the left, the left, irreplacable"

print (str.ljust(45,"+"))

 To the left, the left, irreplacable+++++++++

upper = "THIS IS SO LOUD"

print (upper.lower()) # make string all lowercase

this is so loud

# String lstrip() Method

# The method lstrip() returns a copy of the string in which all chars have been stripped from the beginning of the string 
(default whitespace characters).

str = "     so much cushion    " ;

print (str.lstrip()) # remove cushion on left and right of text so much cushion    

str_1 = "102021020numbers on left and right40121202"

print (str.lstrip('15')) # 15 chars to be trimmed 

     so much cushion    

print (str_1.lstrip('15')) # 15 chars to be trimmed

02021020numbers on left and right40121202

print (str_1.lstrip('40')) # 15 chars to be trimmed

102021020numbers on left and right40121202

print (str_1.lstrip('2')) # chars to be trimmed

102021020numbers on left and right40121202

# String maketrans() Method

###

# The method maketrans() returns a translation table that maps each character in the intabstring into the character at the 
same position in the outtab string. Then this table is passed to the translate() function.

# Both intab and outtab must have the same length.

#

# str.maketrans(intab, outtab]);

# intab -- This is the string having actual characters
# outtab -- This is the string having corresponding mapping character.

# String max() Method

# The method max() returns the max alphabetical character from the string str.

# max(str)

# str -- This is the string from which max alphabetical character needs to be returned.

str = "what is the latest letter in alphabet in this phrase?"

print ("Max character: " + max(str))

Max character: w

# String min() Method

# The method min() returns the min alphabetical character from the string str.

# min(str)

str = "what is the earliest letter in alphabet in this phrase?"

print ("Min character: " + min(str))

Min character:  

print (min(str))

str = "what is the earliest letter in alphabet in this phrase!";

print ("Min character: " + min(str))

Min character:  

str = "this-is-real-string-example....wow!!!";

print ("Min character: " + min(str))

Min character: !

# String replace() Method

# The method replace() returns a copy of the string in which the occurrences of old have been replaced with new, optionally 
restricting the number of replacements to max.

# str.replace(old, new[, max])

str = "this is real. The color is dark."

print (str.replace("is", "is not")) # replace example

this not is not real. The color is not dark.

var = "this is real."

print (var.replace("is", "is not"))

this not is not real.

print (var.replace("is", "isn't"))

thisn't isn't real.

tr = "tree is real'

SyntaxError: EOL while scanning string literal

tr = "tree is real"


print (tr.replace("is", "isn't"))

tree isn't real

# String rfind() Method

# The method rfind() returns the last index where the substring str is found, or -1 if no such index exists, optionally 
restricting the search to string[beg:end].

# str.rfind(str, beg=0 end=len(string))

tr = "tree is real"

sr = "ea"

print(tr.rfind(sr))

print(tr.rfind(sr, 5, 15))

9

# String rindex() Method

# The method rindex() returns the last index where the substring str is found, or raises an exception if no such index 
exists, optionally restricting the search to string[beg:end].

# str.rindex(str, beg=0 end=len(string))

tr = "tree is real"

sr = "ea"

print (tr.rindex(sr))

9

# rjust() Method

# The method rjust() returns the string right justified in a string of length width. Padding is done using the specified 
fillchar (default is a space). The original string is returned if width is less than len(s).

# str.rjust(width[, fillchar])

str = "moving to the right"

print (str.rjust(40, "-"))

---------------------moving to the right
# String rstrip() Method

# The method rstrip() returns a copy of the string in which all chars have been stripped from the end of the string (default 
whitespace characters).

# str.rstrip([chars])
str ="gonna trimming on fat......"
print(str.rstrip())
gonna trimming on fat......

str ="gonna trimming on fat      "
print(str.rstrip())

gonna trimming on fat


print(str.rstrip('10'))

gonna trimming on fat      

# String split() Method

# The method split() returns a list of all the words in the string, using str as the separator (splits on all whitespace if 
left unspecified), optionally limiting the number of splits to num.

# str.split(str="", num=string.count(str)).

str = " first split \n second split \n third split"

print(str.split( ))

['first', 'split', 'second', 'split', 'third', 'split']

print(str.split("\n", 1))

[' first split ', ' second split \n third split']

# String splitlines() Method

# The method splitlines() returns a list with all the lines in string, optionally including the line breaks (if num is 
supplied and is true)

# str.splitlines( num=string.count('\n'))

str = " first split \n second split \n third split"

print(str.splitlines())
[' first split ', ' second split ', ' third split']

print(str.splitlines(2))

[' first split \n', ' second split \n', ' third split']

print(str.splitlines(1))

[' first split \n', ' second split \n', ' third split']

print(str.splitlines(3))

[' first split \n', ' second split \n', ' third split']

# String startswith() Method

# The method startswith() checks whether string starts with str, optionally restricting the matching with the given indices 
start and end.

# str.startswith(str, beg=0,end=len(string));

str = " first split \n second split \n third split"

print(str.startswith('first'))

False

print(str.startswith(' '))

True

# String strip() Method

# The method strip() returns a copy of the string in which all chars have been stripped from the beginning and the end of the 
string (default whitespace characters).

# str.strip([chars]);

str = "-----first split \n second split \n third split----"

print(str.split('-'))

['', '', '', '', '', 'first split \n second split \n third split', '', '', '', '']

print(str.split('-'))

['', '', '', '', '', 'first split \n second split \n third split', '', '', '', '']

# String swapcase() Method

# The method swapcase() returns a copy of the string in which all the case-based characters have had their case swapped.

str ="gonna trimming on fat"

print(str.swapcase())

GONNA TRIMMING ON FAT

var = "GONNA TRIMMING ON FAT"

print(str.swapcase())

GONNA TRIMMING ON FAT

print(var.swapcase())

gonna trimming on fat

# print(str.swapcase())

# The method title() returns a copy of the string in which first characters of all the words are capitalized.

str ="gonna trimming on fat"

print(str.title())

Gonna Trimming On Fat

# String translate() Method

# The method translate() returns a copy of the string in which all characters have been translated using table (constructed with the maketrans() function in the string module), optionally deleting all characters found in the string deletechars.

#str.translate(table[, deletechars]);

# String upper() Method

# The method upper() returns a copy of the string in which all case-based characters have been uppercased.

 str ="gonna trimming on fat"

 

SyntaxError: unexpected indent

str ="gonna trimming on fat"

print(str.upper())

GONNA TRIMMING ON FAT

# String zfill() Method

# The method zfill() pads string on the left with zeros to fill width.

str ="gonna trimming on fat"

print(str.zfill(50))

00000000000000000000000000000gonna trimming on fat

# String isdecimal() Method

# The method isdecimal() checks whether the string consists of only decimal characters. This method are present only on 
unicode objects.

# Note: To define a string as Unicode, one simply prefixes a 'u' to the opening quotation mark of the assignment. Below is 
the example.

str = u"turn3479";

print(str.isdecimal());

False

var = u"17243479";

print(var.isdecimal());

True

# Lists

var = ['a', 'b', 'c', 'd'];

print ("var[2:3]: ", var[2:3]) # print items 2 and 3 in list

var[2:3]:  ['c']

# update list items

list[2] = 'f'

Traceback (most recent call last):

  File "<pyshell#5>", line 1, in <module>

    list[2] = 'f'

TypeError: 'type' object does not support item assignment

var[2] = 'cat' # make item 2 in list now be 'cat' instead

print ("new item 2 in list called var:", var[2])

new item 2 in list called var: cat

# removing list iem

 # removing list item
 
del var[1];

print ("new version of list var;", var[1])

new version of list var; cat

# basic list operations

# concatenation with '+' and repetition with '*'

len(['a', 'b', 'c', 'd']) # length

4

# above 'len' function provides the quantity of items in a list

list1 = ['be', 'see', 'den']

b = var + list1

print ("combination of lists var and list1:", b)

combination of lists var and list1: ['a', 'cat', 'd', 'be', 'see', 'den']

print("list var 3 times:", var * 3)

list var 3 times: ['a', 'cat', 'd', 'a', 'cat', 'd', 'a', 'cat', 'd']

# checking if a value is in a list with membership expression

'a' in var

True

'b' in var # is value of 'b' in the list called var

False

# list iteration

for x in var: print (x)

a

cat

d

# above assign x variable to value of '3'

# next statement above instructs for loop to print 'x' first values of var

###

###

# Indexing, Slicing, and Matrixes

#

T = ['bread', 'cheese', 'jam']

T[2] # offsets start at zero

'jam'

T[-0] # negative: count from the right

'bread'

T[-2] # negative: count from the right

'cheese'

T[1] # offsets start at zero

'cheese'

T[-1] # negative: count from the right

'jam'

T[1:] # slicing fetches sections, in this case items from item number one

['cheese', 'jam']

# Built-in List Functions and Methods

###

# List cmp() Method: compares elements of two lists.

be, me = ['best', 'ever'], ['ever', 'greatest']

len(['a', 'b', 'c', 'd']) # length

4

max(['a', 'b', 'c', 'd']) # max

'd'

min(['a', 'b', 'c', 'd']) # min

'a'

# List list() Method

# The method list() takes sequence types and converts them to lists. This is used to convert a given tuple 
into list.

# Tuple are very similar to lists with only difference that element values of a tuple can not be changed 
and tuple elements are put between parentheses instead of square bracket.

l_tuple = ('apple', 'berry', 'cherry')

l_list = list(l_tuple)

print ("list elements:", l_list)

list elements: ['apple', 'berry', 'cherry']

# several list methods available

####

# List append() Method

new = ['store', 'sale', 'clearance']

new.append('garage') # 'garage' as value in the list called new

print ("list after append:", new)

list after append: ['store', 'sale', 'clearance', 'garage']

# List count() Method

# method count() returns count of how many times obj occurs in list.

new = ['store', 'sale', 'clearance']

print (" value of sale appears", new.count('sale'), " times")

 value of sale appears 1  times

print (" value of store appears", new.count('store'), " time(s)")

 value of store appears 1  time(s)

## List extend() Method

#####

# method extend() appends the contents of seq to list.

####

done = ['finale', 'home stretch', 'complete']

conclude = ['summary', 'cool down']

done.extend(conclude) # add the items of list conclude to list done

print ("Extended list called done:", done)

Extended list called done: ['finale', 'home stretch', 'complete', 'summary', 'cool down']

# List index() Method

# method index() returns the lowest index in list that obj appears.

vcr = ['tape', 'film', 'movie']

print ("Index position of 'movie';", vcr.index('movie'))

Index position of 'movie'; 2

# List insert() Method

# method insert() inserts object obj into list at offset index.

awal = ['left', 'bailed', 'discharged']

awal.insert(1, 'retired')

print ("approved list:", awal)

approved list: ['left', 'retired', 'bailed', 'discharged']

# List pop() Method

# method pop() removes and returns last object or obj from the list.

# list.pop(obj=list[-1])

# obj -- This is an optional parameter, index of the object to be removed from the list.

lremove = ['after', 'year', 'done', 'now']

print ("Remove list dropper:", lremove.pop())

Remove list dropper: now

print ("Remove list dropper:", lremove.pop(1)) # item one remove

Remove list dropper: year

# List remove() Method

# obj -- This is the object to be removed from the list.

# This method does not return any value but removes the given object from the list.

nlist = ['left', 'right', 'up', 'down']

nlist.remove('right');

print("nlist list after removal:", nlist)

nlist list after removal: ['left', 'up', 'down']

# List reverse() Method

#  method reverse() reverses objects of list in place.

# This method does not return any value but reverse the given object from the list

nlist = ['left', 'right', 'up', 'down']

nlist.reverse();

print("nlist list reversed:", nlist)

nlist list reversed: ['down', 'up', 'right', 'left']

# List sort() Method

# method sort() sorts objects of list, use compare func if given.

# list.sort([func])

# This method does not return any value but reverse the given object from the list.

nlist = ['left', 'right', 'up', 'down']

nlist.sort()

print ("sorted list: ", nlist)

sorted list:  ['down', 'left', 'right', 'up']

####

## Python Tuples

####

## Tuples are sequences, just like lists. The differences between tuples and lists are, the tuples cannot be changed unlike lists and tuples use parentheses, whereas lists use square brackets.

tuple_emtpy = (); # empty tuple

tuple_single_val = (15,); # tuple with a single value

tuple_emtpy

()

tuple_single_val

(15,)

tuple_full = (10, 14, 213, 2134)

tuple_full

(10, 14, 213, 2134)

# tuple items cannot be updated or changed

# tuples can be concatenated

tuple_sing_full = tuple_single_val + tuple_full

print(tuple_sing_full)

(15, 10, 14, 213, 2134)

# cannot remove item from tuple

tuple_full = (10, 14, 213, 2134)

del tuple_full # deleting a tuple

print(tuple_full)

Traceback (most recent call last):

  File "<pyshell#131>", line 1, in <module>

    print(tuple_full)

NameError: name 'tuple_full' is not defined

# above error message confirms tuple named tuple_full had been deleted

###

len(tuple_single_val)

1

ntuple = ('left', 'right', 'up', 'down')

tuple_full = (10, 14, 213, 2134)

combo = ntuple + tuple_full # concatenation

print(combo)

('left', 'right', 'up', 'down', 10, 14, 213, 2134)

tuple_full*2 # repetition

(10, 14, 213, 2134, 10, 14, 213, 2134)

14 in tuple_full # membership

True

x = 4

for x in combo: print (x) # print the first x items in tuple called combo

left

right

up

down

10

14

213

2134

# Indexing, Slicing, and Matrixes

##

##

tuple_full = (10, 14, 213, 2134)

tuple_full[2] # Offsets start at zero

213

tuple_full[-2] # Negative: count from the right starting with '-1'

213

tuple_full[1:3] # Slicing fetches sections

(14, 213)

####

# Slicing fetches sections

####

# Any set of multiple objects, comma-separated, written without identifying symbols, i.e., brackets for lists, parentheses for tuples, etc., default to tuples, as indicated in these short examples −

tuple_full = (10, 14, 213, 2134)

len( tuple_full) # length

4

max( tuple_full) # max

2134

min( tuple_full) # min

10

c_list = [ 12, 134, 64, 43, 27] # list variable

tuple(c_list) # converting list variable into a tuple

(12, 134, 64, 43, 27)

# Lists

var = ['a', 'b', 'c', 'd'];

print ("var[2:3]: ", var[2:3]) # print items 2 and 3 in list

var[2:3]:  ['c']

# update list items

list[2] = 'f'

Traceback (most recent call last):

  File "<pyshell#5>", line 1, in <module>

    list[2] = 'f'

TypeError: 'type' object does not support item assignment

var[2] = 'cat' # make item 2 in list now be 'cat' instead

print ("new item 2 in list called var:", var[2])

new item 2 in list called var: cat

# removing list iem

 # removing list item
 
del var[1];

print ("new version of list var;", var[1])

new version of list var; cat

# basic list operations

# concatenation with '+' and repetition with '*'

len(['a', 'b', 'c', 'd']) # length

4

# above 'len' function provides the quantity of items in a list

list1 = ['be', 'see', 'den']

b = var + list1

print ("combination of lists var and list1:", b)

combination of lists var and list1: ['a', 'cat', 'd', 'be', 'see', 'den']

print("list var 3 times:", var * 3)

list var 3 times: ['a', 'cat', 'd', 'a', 'cat', 'd', 'a', 'cat', 'd']

# checking if a value is in a list with membership expression

'a' in var

True

'b' in var # is value of 'b' in the list called var

False

# list iteration

for x in var: print (x)

a

cat

d

# above assign x variable to value of '3'

# next statement above instructs for loop to print 'x' first values of var

###

###

# Indexing, Slicing, and Matrixes

#

T = ['bread', 'cheese', 'jam']

T[2] # offsets start at zero

'jam'

T[-0] # negative: count from the right

'bread'

T[-2] # negative: count from the right

'cheese'

T[1] # offsets start at zero

'cheese'

T[-1] # negative: count from the right

'jam'

T[1:] # slicing fetches sections, in this case items from item number one

['cheese', 'jam']

# Built-in List Functions and Methods

###

# List cmp() Method: compares elements of two lists.

be, me = ['best', 'ever'], ['ever', 'greatest']

len(['a', 'b', 'c', 'd']) # length

4

max(['a', 'b', 'c', 'd']) # max

'd'

min(['a', 'b', 'c', 'd']) # min

'a'

# List list() Method

# The method list() takes sequence types and converts them to lists. This is used to convert a given tuple 
into list.

# Tuple are very similar to lists with only difference that element values of a tuple can not be changed 
and tuple elements are put between parentheses instead of square bracket.

l_tuple = ('apple', 'berry', 'cherry')

l_list = list(l_tuple)

print ("list elements:", l_list)

list elements: ['apple', 'berry', 'cherry']

# several list methods available

####

# List append() Method

new = ['store', 'sale', 'clearance']

new.append('garage') # 'garage' as value in the list called new

print ("list after append:", new)

list after append: ['store', 'sale', 'clearance', 'garage']

# List count() Method

# method count() returns count of how many times obj occurs in list.

new = ['store', 'sale', 'clearance']

print (" value of sale appears", new.count('sale'), " times")

 value of sale appears 1  times

print (" value of store appears", new.count('store'), " time(s)")

 value of store appears 1  time(s)

## List extend() Method

#####

# method extend() appends the contents of seq to list.

####

done = ['finale', 'home stretch', 'complete']

conclude = ['summary', 'cool down']

done.extend(conclude) # add the items of list conclude to list done

print ("Extended list called done:", done)

Extended list called done: ['finale', 'home stretch', 'complete', 'summary', 'cool down']

# List index() Method

# method index() returns the lowest index in list that obj appears.

vcr = ['tape', 'film', 'movie']

print ("Index position of 'movie';", vcr.index('movie'))

Index position of 'movie'; 2

# List insert() Method

# method insert() inserts object obj into list at offset index.

awal = ['left', 'bailed', 'discharged']

awal.insert(1, 'retired')

print ("approved list:", awal)

approved list: ['left', 'retired', 'bailed', 'discharged']

# List pop() Method

# method pop() removes and returns last object or obj from the list.

# list.pop(obj=list[-1])

# obj -- This is an optional parameter, index of the object to be removed from the list.

lremove = ['after', 'year', 'done', 'now']

print ("Remove list dropper:", lremove.pop())

Remove list dropper: now

print ("Remove list dropper:", lremove.pop(1)) # item one remove

Remove list dropper: year

# List remove() Method

# obj -- This is the object to be removed from the list.

# This method does not return any value but removes the given object from the list.

nlist = ['left', 'right', 'up', 'down']

nlist.remove('right');

print("nlist list after removal:", nlist)

nlist list after removal: ['left', 'up', 'down']

# List reverse() Method

#  method reverse() reverses objects of list in place.

# This method does not return any value but reverse the given object from the list

nlist = ['left', 'right', 'up', 'down']

nlist.reverse();

print("nlist list reversed:", nlist)

nlist list reversed: ['down', 'up', 'right', 'left']

# List sort() Method

# method sort() sorts objects of list, use compare func if given.

# list.sort([func])

# This method does not return any value but reverse the given object from the list.

nlist = ['left', 'right', 'up', 'down']

nlist.sort()

print ("sorted list: ", nlist)

sorted list:  ['down', 'left', 'right', 'up']

####

## Python Tuples

####

## Tuples are sequences, just like lists. The differences between tuples and lists are, the tuples cannot be changed 

unlike lists and tuples use parentheses, whereas lists use square brackets.

tuple_emtpy = (); # empty tuple

tuple_single_val = (15,); # tuple with a single value

tuple_emtpy

()

tuple_single_val

(15,)

tuple_full = (10, 14, 213, 2134)

tuple_full

(10, 14, 213, 2134)

# tuple items cannot be updated or changed

# tuples can be concatenated

tuple_sing_full = tuple_single_val + tuple_full

print(tuple_sing_full)

(15, 10, 14, 213, 2134)

# cannot remove item from tuple

tuple_full = (10, 14, 213, 2134)

del tuple_full # deleting a tuple

print(tuple_full)

Traceback (most recent call last):

  File "<pyshell#131>", line 1, in <module>

    print(tuple_full)

NameError: name 'tuple_full' is not defined

# above error message confirms tuple named tuple_full had been deleted

###

len(tuple_single_val)

1

ntuple = ('left', 'right', 'up', 'down')

tuple_full = (10, 14, 213, 2134)

combo = ntuple + tuple_full # concatenation

print(combo)

('left', 'right', 'up', 'down', 10, 14, 213, 2134)

tuple_full*2 # repetition

(10, 14, 213, 2134, 10, 14, 213, 2134)

14 in tuple_full # membership

True

x = 4

for x in combo: print (x) # print the first x items in tuple called combo

left

right

up

down

10

14

213

2134

# Indexing, Slicing, and Matrixes

##

##

tuple_full = (10, 14, 213, 2134)

tuple_full[2] # Offsets start at zero

213

tuple_full[-2] # Negative: count from the right starting with '-1'

213

tuple_full[1:3] # Slicing fetches sections

(14, 213)

####

# Slicing fetches sections

####

# Any set of multiple objects, comma-separated, written without identifying symbols, i.e., brackets for lists, 

parentheses for tuples, etc., default to tuples, as indicated in these short examples −

tuple_full = (10, 14, 213, 2134)

len( tuple_full) # length

4

max( tuple_full) # max

2134

min( tuple_full) # min

10

c_list = [ 12, 134, 64, 43, 27] # list variable

tuple(c_list) # converting list variable into a tuple

(12, 134, 64, 43, 27)


# Python Dictionary

a_dict = {'color' : 'brown', 'mouth' : 'teeth'}

print (a_dict) #printing a_dict

{'mouth': 'teeth', 'color': 'brown'}

# updating dictionary

a_dict = {'color' : 'brown', 'mouth' : 'teeth'}

a_dict['color'] = 'black' # new value for key

a_dict['shape'] = 'round' # adding new entry

print("a_dict items:", a_dict)

a_dict items: {'mouth': 'teeth', 'color': 'black', 'shape': 'round'}

del a_dict['color'] # remove entry with key 'color'

print("new a_dict:", a_dict)

new a_dict: {'mouth': 'teeth', 'shape': 'round'}

a_dict.clear() # remove all entries in dict

print("new a_dict:", a_dict)

new a_dict: {}

del a_dict # delete the entire dictionary

# properties

b_dict = {'color' : 'black', 'mouth' : 'ears'}

print("b_dict['color'] : ", b_dict['color'])

b_dict['color'] :  black

# keys in dictionary must be immutable such as strings, numbers or tuples

###

b_dict = {'color' : 'black', 'mouth' : 'ears'}

len(b_dict) # length

2

print("values : %s" % str (b_dict))

values : {'mouth': 'ears', 'color': 'black'}

# type() method

b_dict = {'color' : 'black', 'mouth' : 'ears'}

print ("variable type : %s" % type (b_dict))

variable type : <class 'dict'>

# methods with description

#

# dictionary clear() Method

b_dict = {'color' : 'black', 'mouth' : 'ears'}

print ("Start Len : %d" %  len(b_dict))

Start Len : 2

b_dict.clear

<built-in method clear of dict object at 0x02A4C418>

b_dict.clear()

print ("Start Len : %d" %  len(b_dict))

Start Len : 0

c_dict = b_dict.copy()

print("c_dict : ", c_dict)

c_dict :  {}

print("b_dict : ", b_dict)

b_dict :  {}

d_dict = {'color' : 'black', 'mouth' : 'ears'}

e_dict = d_dict.copy()

print("e_dict : ", e_dict)

e_dict :  {'color': 'black', 'mouth': 'ears'}

print ("New Dictinary : %s" %  str(e_dict))

New Dictinary : {'color': 'black', 'mouth': 'ears'}

# fromkeys() Method

# dict.fromkeys(seq[, value]))

seq = [1, 2, 3]

d_dict.fromkeys(seq, '10')

{1: '10', 2: '10', 3: '10'}

f_dict = d_dict.fromkeys(seq, '10')

print ("New Dictionary : %s" %  str(f_dict))

New Dictionary : {1: '10', 2: '10', 3: '10'}

# dictionary get() Method

##

# method get() returns a value for the given key. If key is not available then returns default value None.

# dict.get(key, default=None)


d_dict = {'color' : 'black', 'mouth' : 'ears'}

print ("Value : %s" %  d_dict.get('mouth'))

Value : ears

print ("Value : %s" %  d_dict.get('Paid', "Often"))

Value : Often

# has_key() Method

# method has_key() returns true if a given key is available in the dictionary, otherwise it returns a false.

g_dict = {'color' : 'green', 'mouth' : 'toe'}

dict = {'Name': 'Zara', 'Age': 7}

###

# dictionary items() Method

# method items() returns a list of dict's (key, value) tuple pairs

cd_dict = {'Name': 'Tim', 'Age': 20}

print("Values : %s" % dict.items())

Values : dict_items([('Age', 7), ('Name', 'Zara')])

ye_dict = {'Name': 'Tom', 'Age': 16}

print("Items : %s" % ye_dict.items())

Items : dict_items([('Age', 16), ('Name', 'Tom')])

print("Keys : %s" % ye_dict.keys())

Keys : dict_keys(['Age', 'Name'])

# keys in dictionary

g_dict = {'color' : 'green', 'mouth' : 'toe'}

print("Keys : %s" % g_dict.keys())

Keys : dict_keys(['mouth', 'color'])

print ("Value : %s " % g_dict.setdefault('mouth', False))

Value : toe 

abc = {'igloo' : 'snow', 'beach' : 'sand'}

g_dict.update(abc) # adding 'abc' dictionary to g_dict dictionary

print ("Updated dictionary: ", g_dict)

Updated dictionary:  {'igloo': 'snow', 'beach': 'sand', 'mouth': 'toe', 'color': 'green'}

print("Values of g_dict: ", g_dict.values())

Values of g_dict:  dict_values(['snow', 'sand', 'toe', 'green'])

# Python Date & Time

# tick is the unit of time which is a floating point number in units of

# seconds

###

# function time.time() returns the current system time in ticks since 12:00am, January 1, 1970(epoch).

import time # required to include time module

ticks = time.time()

print("ticks count since 12:00am, Jan 1, 1970:", ticks)

ticks count since 12:00am, Jan 1, 1970: 1453511758.10451

# dates before epoch, 12:00am Jan 1, 1970 can't be represented as ticks

# the cutoff in the future for tick format

# is year 2038 for UNIX and Windows computer systems

#

# Much of Pythons time functions handle time as tuple of9 numbers

# 4 digit year ex. 2008

# Month of 1 to 12

# DAy of 1 to 31

# Hour of 0 to 23

# Minute of 0 to 59

# Second of 0 to 61 (60 or 61 are leap-seconds)

# day of week 0 to 6 (0 is Monday)

# day of year of 1 of 366 (julian day)

# daylight savings -1, 0, 1, -1 means library determines DST

ticks = time.time()

ticks = time.time()

print("ticks count since 12:00am, Jan 1, 1970:", ticks)

ticks count since 12:00am, Jan 1, 1970: 1453512282.9735308

# above tuple equivalent to struct_time structure

# tm_year 2008

# tm_mon 1 to 12

# tm_mday 1 to 31

# tm_hour 0 to 23

# tm_min 0 to 59

# tm_sec 0 to 61 (60 or 61 are leap-seconds)

# tm_wday 0 to 6 (0 is Monday)

# tm_yday 1 to 366 (julian day)

# tm_isdst -1, 0, 1, -1 means library determines DST

import time

localtime = time.localtime(time.time())

print ("local current :", localtime)

local current : time.struct_time(tm_year=2016, tm_mon=1, tm_mday=22, tm_hour=19, tm_min=33, 

tm_sec=34, tm_wday=4, tm_yday=22, tm_isdst=0)

curr_time = time.localtime(time.time())

print ("current time : ", curr_time)

current time :  time.struct_time(tm_year=2016, tm_mon=1, tm_mday=22, tm_hour=19, tm_min=36, 
tm_sec=24, tm_wday=4, tm_yday=22, tm_isdst=0)

# can format any time as per your requirement, but simple method to get time in readable format is 
asctime()

import time;

localtime = time.asctime(time.localtime(time.time()))

print("local current time: " , localtime)

local current time:  Fri Jan 22 19:57:23 2016

nextime = time.asctime(time.localtime(time.time()))

print("next time:", nextime)

next time: Fri Jan 22 19:59:18 2016

# get calendar

import calendar

gmonth = calendar.month(2015, 12)

print("This is the calendar month:")

This is the calendar month:

print (gmonth)

   December 2015

Mo Tu We Th Fr Sa Su

    1  2  3  4  5  6

 7  8  9 10 11 12 13

14 15 16 17 18 19 20

21 22 23 24 25 26 27

28 29 30 31

import calendar

jan_month = calendar.month(2016,1)

print("Jan 2016 calendar:")

Jan 2016 calendar:

print(jan_month)

    January 2016

Mo Tu We Th Fr Sa Su

             1  2  3

 4  5  6  7  8  9 10

11 12 13 14 15 16 17

18 19 20 21 22 23 24

25 26 27 28 29 30 31



# methods for time module

#

# time altzone() Method

# returns the offset of the local DST timezone, in seconds west of UTC, if one is defined. This is negative 

if the local DST timezone is east of UTC (as in Western Europe, including the UK). Only use this if daylight 

is nonzero.

import time

print("time.altzone %d " % time.altzone)

time.altzone 18000 

print("seconds west of UTC time %d " % time.altzone)

seconds west of UTC time 18000 

# time asctime() Method

import time

asctime_ex = time.asctime(time.localtime(time.time()))

print("this an example of asctime:", asctime_ex)

this an example of asctime: Fri Jan 22 20:11:23 2016

# another approach to getting asctime

import time

a = time.localtime()

print(a) # local time in standard format

time.struct_time(tm_year=2016, tm_mon=1, tm_mday=22, tm_hour=20, tm_min=12, tm_sec=51, 
tm_wday=4, tm_yday=22, tm_isdst=0)

print("local time in asctime format: %s" % time.asctime(a))

local time in asctime format: Fri Jan 22 20:12:51 2016

# time clock() Method

# method clock() returns the current processor time as a floating point number expressed in seconds on 
Unix.

# On Windows, this function returns wall-clock seconds elapsed since the first call to this function, as a 
floating point number, based on the Win32 function QueryPerformanceCounter.

import time

def procedure():

	time.sleep(2.5)

# measure process time

t0 = time.clock()

procedure()

print (time.clock() - t0, "seconds process time")

39.43636092396363 seconds process time

import time

def procedure():

	time.sleep(5)

t1 = time.clock()

procedure()

print(time.clock() - t1, "seconds process time")

35.26896844666699 seconds process time

# measure wall time

t2 = time.time()

procedure()

print (time.time() - t2, "seconds wall time")

37.642865896224976 seconds wall time

t3 = time.time()

procedure()

print(time.time() - t3, "seconds wall time")

29.172051191329956 seconds wall time

# time ctime() Method

#

# method ctime() converts a time expressed in seconds since the epoch to a string representing local 
time. If secs is not provided or None, the current time as returned by time() is used. This function is equivalent to asctime(localtime(secs)). Locale information is not used by ctime().

# time.ctime([ sec ])

import time

print("time.ctime() : %s" % time.ctime())

time.ctime() : Fri Jan 22 20:32:12 2016

import time

print("time.ctime() : %s" % time.ctime())

time.ctime() : Fri Jan 22 20:32:36 2016

# time gmtime() Method

# method gmtime() converts a time expressed in seconds since the epoch to a struct_time in UTC in which the dst flag is always zero. If secs is not provided or None, the current time as returned by time() is used.

#

# time.gmtime([ sec ])

import time

# time localtime() Method

# method localtime() is similar to gmtime() but it converts number of seconds to local time. If secs is not provided or None, the current time as returned by time() is used. The dst flag is set to 1 when DST applies to the given time.

import time

# time mktime() Method

# method mktime() is the inverse function of localtime(). Its argument is the struct_time or full 9-tuple and it returns a floating point number, for compatibility with time().

import time

n = (2015, 3, 16, 8, 12, 50, 2, 34, 0)

seconds  = time.mktime(n)

print("time.mktime(n): %f" % seconds)

time.mktime(n): 1426515170.000000

print("asctime(localtime(seonds)): %s" % time.asctime(time.localtime(seconds)))

asctime(localtime(seonds)): Mon Mar 16 09:12:50 2015

# time sleep() method

# method sleep() suspends execution for the given number of seconds

# the argument may be a floating number to indicate a more precise sleep time

# actual suspension time may be less than that requested because any caught signal will terminate the 
sleep() following execution of that signal's catching routine.

# syntax time.sleep(t)

import time

print ("Start : %s" % time.ctime())

Start : Fri Jan 22 20:49:25 2016

time.sleep(10)

print("end: %s" % time.ctime())

end: Fri Jan 22 20:50:15 2016

# time strftime() Method

# method strftime() converts a tuple or struct_time representing a time as returned by gmtime() or 
localtime() to a string as specified by the format argument

# syntax time.strftime(format[, t])

# there many directive options

# v

# %a - abbreviated weeday name

# A full weekday name

# %b abbreviated month name

# %B full month name

# %c preferred date and time represent

# %C century number (the year divided by 100, range 00 to 99)

# %d day of the month (01 to 31)

# %D same as %m/%d/%y

# %e day of month (1 to 31)

# %g like %G, but without the century

# %G 4 digit year corresponding to the ISO week number (see %V)

# %h same as %b

# %H hour, using a 24 hour clock (00 to 23)

# %I hour, using a 12 hour clock (01 to 12)

# j day of year (001 to 366)

# %m monht (01 to 12)

# %M minute

# %n newline character

# %p either am or pm according to the given time value

# %r time in am or pm notation

# %R time in 24 hour notation

# %S second

# %t tab character

# %T current time, equl to %H:%M:%S

# %u weekday as a number (1 to 7), Monday=1. Warning: In Sun Solaris Sunday=1

# %U week number of current year starting with the first sunday as the first day of the first week

# %V The ISO 8601 week number of the current year (01 to 53) where week 1 is the first week that has at least 4 days in the current year, an with Monday as the first day of the week

# %W week number of the current year, starting with the first Monday as the first day of the first week

# %w day of the week as a decimal, Sunday=0

# %x preferred date representation without the time

# %X preferred time representation with the date

# %y year without a century (range 00 to 99)

# %Y year including the century

# %Z or %z time zone or name or abbreviation

# %% a lateral % character

import time

t = (2009, 2, 17, 17, 3, 38, 1, 48, 0)

t = time.mktime(t)

print(time.strftime("%b %d %Y %H:%M:S", time.gmtime(t)))

Feb 17 2009 23:03:S

print(time.strftime("%b %d %Y %H:%M:%S", time.gmtime(t)))

Feb 17 2009 23:03:38

print(time.strftime("%m %e %y %h:%m:%S", time.gmtime(t)))

02 17 09 Feb:02:38

print(time.strftime("%m %e %y %H:%M:%S", time.gmtime(t)))

02 17 09 23:03:38

# time strptime() Method

# method strptime() parses a string representing a time according to a format. The return value is a struct_time as returned by gmtime() or localtime().

# time.strptime(string[, format]) syntax

import time

struct_time = time.strptime("30 Nov 00", "%d %b %y")

# time time() method

# method time() returns the time as a floating point number expressed in seconds since the epoch, in UTC.

import time

print("time.time(): %f" % time.time())

time.time(): 1453521505.131227

print (time.localtime( time.time() ) )

time.struct_time(tm_year=2016, tm_mon=1, tm_mday=22, tm_hour=21, tm_min=59, tm_sec=11, tm_wday=4, tm_yday=22, tm_isdst=0)

print(time.localtime( time.time() ) )

time.struct_time(tm_year=2016, tm_mon=1, tm_mday=22, tm_hour=21, tm_min=59, tm_sec=42, tm_wday=4, tm_yday=22, tm_isdst=0)

print(time.asctime(time.localtime(time.time())))

Fri Jan 22 22:02:27 2016

# time tzset() Method

# method tzset() resets the time conversion rules used by the library routines. The environment variable TZ specifies how this is done.

# std offset [dst [offset [, start [/time], end [/time]]]]

# time.tzset()

import time

import os

os.environ['TZ'] = 'EST+05EDT,M4.1.0,M10.5.0'

time.tzset()

print(time.strftime('%X %x %Z'))

22:09:51 01/22/16 Central Standard Time

os.environ['TZ'] = 'AEST-10AEDT-11,M10.5.0,M3.5.0'

print (time.strftime('%X %x %Z'))

22:10:48 01/22/16 Central Standard Time

# attribute with description

time.timezone

21600

time.tzname

('Central Standard Time', 'Central Daylight Time')

# Attribute time.tzname is a pair of locale-dependent strings, which are the names of the local time zone without and with DST, respectively.

#Attribute time.timezone is the offset in seconds of the local time zone (without DST) from UTC (>0 in the Americas; <=0 in most of Europe, Asia, Africa).

time.timezone

21600

# calendar module

# function with description

# calendar.calendar(year,w=2,L=1,c=6)

# Returns a multiline string with a calendar for year year formatted into three columns separated by c spaces. w is the width in characters of each date; each line has length 21*w+18+2*c. l is the number of lines for each week.

# calendar.calendar(year,w=2,l=1,c=6)

calendar.calendar(2015,w=3,l=1,c=4)

'                                           2015\n\n          January                        February                        March\nMon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun\n              1   2   3   4                              1                              1\n  5   6   7   8   9  10  11      2   3   4   5   6   7   8      2   3   4   5   6   7   8\n 12  13  14  15  16  17  18      9  10  11  12  13  14  15      9  10  11  12  13  14  15\n 19  20  21  22  23  24  25     16  17  18  19  20  21  22     16  17  18  19  20  21  22\n 26  27  28  29  30  31         23  24  25  26  27  28         23  24  25  26  27  28  29\n                                                               30  31\n\n           April                           May                            June\nMon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun\n          1   2   3   4   5                      1   2   3      1   2   3   4   5   6   7\n  6   7   8   9  10  11  12      4   5   6   7   8   9  10      8   9  10  11  12  13  14\n 13  14  15  16  17  18  19     11  12  13  14  15  16  17     15  16  17  18  19  20  21\n 20  21  22  23  24  25  26     18  19  20  21  22  23  24     22  23  24  25  26  27  28\n 27  28  29  30                 25  26  27  28  29  30  31     29  30\n\n            July                          August                       September\nMon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun\n          1   2   3   4   5                          1   2          1   2   3   4   5   6\n  6   7   8   9  10  11  12      3   4   5   6   7   8   9      7   8   9  10  11  12  13\n 13  14  15  16  17  18  19     10  11  12  13  14  15  16     14  15  16  17  18  19  20\n 20  21  22  23  24  25  26     17  18  19  20  21  22  23     21  22  23  24  25  26  27\n 27  28  29  30  31             24  25  26  27  28  29  30     28  29  30\n                                31\n\n          October                        November                       December\nMon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun    Mon Tue Wed Thu Fri Sat Sun\n              1   2   3   4                              1          1   2   3   4   5   6\n  5   6   7   8   9  10  11      2   3   4   5   6   7   8      7   8   9  10  11  12  13\n 12  13  14  15  16  17  18      9  10  11  12  13  14  15     14  15  16  17  18  19  20\n 19  20  21  22  23  24  25     16  17  18  19  20  21  22     21  22  23  24  25  26  27\n 26  27  28  29  30  31         23  24  25  26  27  28  29     28  29  30  31\n                                30\n'

calendar.calendar(2015,w=2,l=1,c=6)

'                                  2015\n\n      January                   February                   March\nMo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su\n          1  2  3  4                         1                         1\n 5  6  7  8  9 10 11       2  3  4  5  6  7  8       2  3  4  5  6  7  8\n12 13 14 15 16 17 18       9 10 11 12 13 14 15       9 10 11 12 13 14 15\n19 20 21 22 23 24 25      16 17 18 19 20 21 22      16 17 18 19 20 21 22\n26 27 28 29 30 31         23 24 25 26 27 28         23 24 25 26 27 28 29\n                                                    30 31\n\n       April                      May                       June\nMo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su\n       1  2  3  4  5                   1  2  3       1  2  3  4  5  6  7\n 6  7  8  9 10 11 12       4  5  6  7  8  9 10       8  9 10 11 12 13 14\n13 14 15 16 17 18 19      11 12 13 14 15 16 17      15 16 17 18 19 20 21\n20 21 22 23 24 25 26      18 19 20 21 22 23 24      22 23 24 25 26 27 28\n27 28 29 30               25 26 27 28 29 30 31      29 30\n\n        July                     August                  September\nMo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su\n       1  2  3  4  5                      1  2          1  2  3  4  5  6\n 6  7  8  9 10 11 12       3  4  5  6  7  8  9       7  8  9 10 11 12 13\n13 14 15 16 17 18 19      10 11 12 13 14 15 16      14 15 16 17 18 19 20\n20 21 22 23 24 25 26      17 18 19 20 21 22 23      21 22 23 24 25 26 27\n27 28 29 30 31            24 25 26 27 28 29 30      28 29 30\n                          31\n\n      October                   November                  December\nMo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su\n          1  2  3  4                         1          1  2  3  4  5  6\n 5  6  7  8  9 10 11       2  3  4  5  6  7  8       7  8  9 10 11 12 13\n12 13 14 15 16 17 18       9 10 11 12 13 14 15      14 15 16 17 18 19 20\n19 20 21 22 23 24 25      16 17 18 19 20 21 22      21 22 23 24 25 26 27\n26 27 28 29 30 31         23 24 25 26 27 28 29      28 29 30 31\n                          30\n'

# calendar.firstweekday()

calendar.firstweekday()

0

# above '0' is Monday

# calendar.isleap(year)

calendar.isleap(2018) # returns True if is leap year else False

False

# calendar.leapdays(y1,y2) # return num of leap yrs in range of y1 to y2

calendar.leapdays(205,2016)

439

# calendar.leapdays(y1,y2) # return num of leap days in range of y1 to y2

# calendar.month(year,month,w=2,l=1)

# Returns a multiline string with a calendar for month month of year year, one line per week plus two header lines. w is the width in characters of each date; each line has length 7*w+6. l is the number of lines for each week.

calendar.month(2014,12,w=2,l=1)

'   December 2014\nMo Tu We Th Fr Sa Su\n 1  2  3  4  5  6  7\n 8  9 10 11 12 13 14\n15 16 17 18 19 20 21\n22 23 24 25 26 27 28\n29 30 31\n'

# calendar.monthcalendar(year,month)

# Returns a list of lists of ints. Each sublist denotes a week. Days outside month month of year year are set to 0; days within the month are set to their day-of-month, 1 and up.

calendar.monthcalendar(2015,6)

[[1, 2, 3, 4, 5, 6, 7], [8, 9, 10, 11, 12, 13, 14], [15, 16, 17, 18, 19, 20, 21], [22, 23, 24, 25, 26, 27, 28], [29, 30, 0, 0, 0, 0, 0]]

# calendar.monthrange(year, month)

# Returns two integers. The first one is the code of the weekday for the first day of the month month in year year; the second one is the number of days in the month. Weekday codes are 0 (Monday) to 6 (Sunday); month numbers are 1 to 12.

calendar.monthrange(2016,3)

(1, 31)

calendar.prcal(2013,w=2,l=1,c=6)

                                  2013

      January                   February                   March
Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
    1  2  3  4  5  6                   1  2  3                   1  2  3
 7  8  9 10 11 12 13       4  5  6  7  8  9 10       4  5  6  7  8  9 10
14 15 16 17 18 19 20      11 12 13 14 15 16 17      11 12 13 14 15 16 17
21 22 23 24 25 26 27      18 19 20 21 22 23 24      18 19 20 21 22 23 24
28 29 30 31               25 26 27 28               25 26 27 28 29 30 31

       April                      May                       June
Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
 1  2  3  4  5  6  7             1  2  3  4  5                      1  2
 8  9 10 11 12 13 14       6  7  8  9 10 11 12       3  4  5  6  7  8  9
15 16 17 18 19 20 21      13 14 15 16 17 18 19      10 11 12 13 14 15 16
22 23 24 25 26 27 28      20 21 22 23 24 25 26      17 18 19 20 21 22 23
29 30                     27 28 29 30 31            24 25 26 27 28 29 30

        July                     August                  September
Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
 1  2  3  4  5  6  7                1  2  3  4                         1
 8  9 10 11 12 13 14       5  6  7  8  9 10 11       2  3  4  5  6  7  8
15 16 17 18 19 20 21      12 13 14 15 16 17 18       9 10 11 12 13 14 15
22 23 24 25 26 27 28      19 20 21 22 23 24 25      16 17 18 19 20 21 22
29 30 31                  26 27 28 29 30 31         23 24 25 26 27 28 29
                                                    30

      October                   November                  December
Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su      Mo Tu We Th Fr Sa Su
    1  2  3  4  5  6                   1  2  3                         1
 7  8  9 10 11 12 13       4  5  6  7  8  9 10       2  3  4  5  6  7  8
14 15 16 17 18 19 20      11 12 13 14 15 16 17       9 10 11 12 13 14 15
21 22 23 24 25 26 27      18 19 20 21 22 23 24      16 17 18 19 20 21 22
28 29 30 31               25 26 27 28 29 30         23 24 25 26 27 28 29
                                                    30 31

# calendar.prmonth(year,month, w=2,l=1)

calendar.prmonth(2013,4,w=2,l=1)

     April 2013
Mo Tu We Th Fr Sa Su
 1  2  3  4  5  6  7
 8  9 10 11 12 13 14
15 16 17 18 19 20 21
22 23 24 25 26 27 28
29 30
 
calendar.setfirstweekday(4)

time.time

<built-in function time>

time.localtime()

time.struct_time(tm_year=2016, tm_mon=1, tm_mday=22, tm_hour=22, tm_min=28, tm_sec=36, 
tm_wday=4, tm_yday=22, tm_isdst=0)

time.time()

1453523324.831408

# calendar.timegm(tupletime)

# The inverse of time.gmtime: accepts a time instant in time-tuple form and returns the same instant as 
a floating-point number of seconds since the epoch.

a = time.localtime

# calendar.weekday(year,month,day)

# Returns the weekday code for the given date. Weekday codes are 0 (Monday) to 6 (Sunday); month numbers are 1 (January) to 12 (December).

calendar.weekday(2015,5,16)

5

# other modules datetime, pytz, dateutil

# Python Functions

# functions created by the user are called user-defined functions

# need to begin a function with def keyword then function name and parentheses

# the code block of a function needs to begin with a colo (:) and be indented

# following is syntax of defining a function

# def functionname (parameters ) :

	# "function_docstring"
	
	# function_suite
	
	# return [expression]
	
# example

def printme(str):

	"this user defined function prints a passed string into this function"

	print str

def printme(str):

	"this user defined function prints a passed string into this function"

	print (str)

	return

# how to call a function

# defining function

def printme(str):

	"this prints a passed string into this function"

	print(str)

	return;

# calling printme function, user defined function

printme("A result of calliing user defined printme function")

A result of calliing user defined printme function

printme("hi new function")

hi new function

def numprint(int):

	"this prints a passed integer into this function"

	print(int)

	return;


numprint(145)

145

# in python parameters or arguments are passed by reference

# thus, if what an argument refers to is changed within a function then the change reflects back in calling that function

# funtion being defined

def changeme(mylist):

	"This changes a passed list into this function"

	mylist.append([1,2,3,4]);

	print("Values inside the function:", mylist)

	return

# calling the changeme function created

mylist = [14, 3, 4, 6];

changeme( mylist);

Values inside the function: [14, 3, 4, 6, [1, 2, 3, 4]]

def changeme(mylist):

	"This changes a passed list into this function"

	mylist.append([15,34,27,10])

	print("Values in this function:", mylist)

	return



mylist = [3,4,6,19]

changeme(mylist)

Values in this function: [3, 4, 6, 19, [15, 34, 27, 10]]


# user defined function that overwrites existing arguments in a list:

# defining such a function

def replacelist(clist):

	"This replaces the items in the passed list into this function"

	clist = [23,19,25,16] # This assigns new reference in clist

	print("Items in function:", clist)

	return


# calling user defined replacelist function

clist=[10,35,98,15];

replacelist(clist);

Items in function: [23, 19, 25, 16]

print(clist)

[10, 35, 98, 15]

# as seen above the values in clist are local to clist so calling clist within in the replacelsit user defined function did not change the values local to the clist list variable

# There are different types of formal argument types for a function including a required argument, keyword argument, default argument, variable length argument

# required arguments

# required arguemnts need to written in correct positional order to match function definition exactly else a syntax error will be generated

# user defined function

def prntstrg(str):

	"prints passed string into this function"

	print(str)

	return;


# calling prntstrg user defined function

var = "the lenthy string"

prntstrg(var) # now function should work

the lenthy string

# keyword arguments

# keyword arguments in function calls let caller indentify the funtion arguments by the parameter name

# usage of keyword arguments can allow the skipping of some arguments or placing the in a different order

# in this case python interpreter uses keywords provided to match values with parameters

# defining a function

def printer(str):

	"prints passed string into this function"

	print(str)

	return;

# calling user defined printer function

printer(str = "last name ever first name greatest - drake" )

last name ever first name greatest - drake

# another example of keyword argument usage

# defining function

def id_experience(origin, tenure):

	"prints passed info into this function"

	print("Origin:", origin)

	print("Age:", age)

	return;


# call id_experience function

id_experience(origin= "Paris", tenure=15)

Origin: Paris

def id_experience(origin,tenure):

	"prints passed info into this function"

	print("Origin:", origin)

	print("Tenure:", tenure)

	return;

id_experience(origin="Cali", tenure=12)

Origin: Cali

Tenure: 12

# default arguments

# defining function

def printdata(name, age=25):

	"This prints a passed info into this function"

	print("Name:", name)

	print("Age", age)

	return;

# now you can call printdata function

printdata(age=14, name="kitten")

Name: kitten

Age 14

printdata(name="bestie")

Name: bestie

Age 25

# variable length argument

# variable length arguments are not named in the function definition but are but in this case user may need to process function for more arguments than specified in definition of the function.

# syntax for a function with non-keyword variable argument follows

# def functionname([formal_args,] "var_args_tuple):

# 	"funtion_docstring"

#	function_suite

# 	return [expression]

# def functionname([formal_args,] *var_args_tuple):

# 	"funtion_docstring"

#	function_suite

# 	return [expression]


# function definition

def printdata(term1, *vartuple):

	"prints variable passed arguments"

	print("Output is:")

	print(term1)

	for var in vartuple:

		print(var)

	return;


# calling printdata function

printdata(10)

Output is:

10

printdata(70,60,50)

Output is:

70

60

50

# annonymous functions

# functions are classified as anonymous when they aren't declared by using the def keyword.

# the lambda keyword is useable to create small anonymous functions

# additional details on anonymous functions http://www.tutorialspoint.com/python/python_functions.htm

# lambda [arg1 [,arg2,......argn]]:expression # syntax

# example of function definition with lambda

sum = lambda arg1, arg2: arg1 + arg2;

# call sum as a function

print("total value:", sum(15,10))

total value: 25

print("total value", sum(4,5))

total value 9

difference = lambda arg1, arg2: arg1 - arg2;

print("value of differnce:", difference(10,5))

value of differnce: 5

# return statement

# return [expression] statement exits function

# define function with return statement argument

def difference(arg1, arg2):
	
	# minus arg2 from arg1 and return difference

	distance = arg1 - arg2
	
	print("Inside function:", distance)
	
	return distance;


# call difference function with return expression

distance = difference(25, 12);

Inside function: 13

print("outside function:", distance)

outside function: 13


# in Python, there are Global and local variables

user = input("Enter your input: ");

Enter your input: sunday

print("day is ", user)

day is  sunday

# renaming and deleting files

# renaming and deleting function part of Python OS module, need import

# rename() method: os.rename(current_file_name, new_file_name)

import os # importing the Python os module

os.rename("hello.py", "first.py")

file = open("first.py")

file.closed

False

detail = file.read()


print("position ", file.tell())

position  0

print(detail)

detail

''

file.close()

file.closed

True

file = open("first.py", "r+")

file.closed

False

detail = file.read()

print("position ", file.tell())

position  0

print(detail)

os.rename("lion.txt", "panther.txt")

file = open("panther.txt", "r+")

file.closed

False

detail = file.read()

print(detail)

tigers have stripes.

print("position ", file.tell())

position  22

file.name

'panther.txt'

file.write(" \n there are many feline animals. \n")

35

file.close()

file = open("panther.txt", "r+")

file.closed

False

detail = file.read()

print(detail)

tigers have stripes.
 
 there are many feline animals. 


# remove() method: to delete files ; os.remove(file_name)

import os

text = open("old_file.txt", "r+")

words = text.read()

print(words)

tigers have stripes.
 
 there are many feline animals. 

text.name

'old_file.txt'

text.mode

'r+'

text.close()

text.closed

True

import os

os.remove("old_file.txt") # deleting file with remove() method

message = open("old_file.txt") # testing if still exists

Traceback (most recent call last):

  File "<pyshell#78>", line 1, in <module>

    message = open("old_file.txt") # testing if still exists

FileNotFoundError: [Errno 2] No such file or directory: 'old_file.txt'


# OS module has methods for creating, removing, changing directories

# mkdir() method in OS module, create directories in current directory

# mkdir() method: os.mkdir("newdir")

import os # importing os module

os.mkdir("data") # create directory "data"

# chdir() Method: os.chdir("newdir")

import os

# getcwd() method: displays the current working directory; os.getcwd()

import os

os.getcwd() # get current working directory path

'C:\\Users\\ndikuman\\AppData\\Local\\Programs\\Python\\Python35-32'

#C:\Users\ndikuman\AppData\Local\Programs\Python\Python35-32 is folder path

# working directory path uses double back slashes

os.chdir("C:\\Users\\ndikuman\\AppData\\Local\\Programs\\Python\\Python35-32\\data")

os.getcwd()

'C:\\Users\\ndikuman\\AppData\\Local\\Programs\\Python\\Python35-32\\data'

file.name

'panther.txt'

os.chdir("C:\\Users\\ndikuman\\AppData\\Local\\Programs\\Python\\Python35-32")

file.name

'panther.txt'

file = open("panther.txt")

file.closed

False

file.close()

file.closed

True

os.chdir("C:\\Users\\ndikuman\\AppData\\Local\\Programs\\Python\\Python35-32\\data")

file = open("panther_data.txt")

info = file.read()

print("file text: ", info)

file text:  tigers have stripes.
 
 there are many feline animals. 

file.close

<built-in method close of _io.TextIOWrapper object at 0x02D98DB0>

file.closed

False

file.close()

file.closed

True

# rmdir() Method: deletes the directory; os.rmdir('dirname')

import os

os.mkdir('tester')

os.mkdir('allfull') # new directory 'allfull'

os.rmdir('allfull') # deleting directory 'allfull'

# Python 'File' Object Methods provides functions to manipulate files

# file.close() - close file

# file.flush() - Flush the internal buffer, like stdio's fflush. This may be a no-op on some file-like objects.

# file.fileno() - Returns the integer file descriptor that is used by the underlying implementation to request I/O operations from the operating system.

# file.isatty() - Returns True if the file is connected to a tty(-like) device, else False.

# file.next() - Returns the next line from the file each time it is being called.

# file.read([size]) - 	

file.read([size])

# file.read([size]) Reads at most size bytes from the file (less if the read hits EOF before obtaining size bytes).

# file.readline([size] Reads one entire line from the file. A trailing newline character is kept in the string.

# file.readlines([sizehint]) Reads until EOF using readline() and return a list containing the lines. If the optional sizehint argument is present, instead of reading up to EOF, whole lines totalling approximately sizehint bytes (possibly after rounding up to an internal buffer size) are read.

# file.seek(offset [, whence]) Sets the file's current position

# file.tell() Returns the file's current position

# file.truncate([size]) Truncates the file's size. If the optional size argument is present, the file is truncated to (at most) that size.

# file.write(str) Writes a string to the file. There is no return value.

# file.writelines(sequence) Writes a sequence of strings to the file. The sequence can be any iterable object producing strings, typically a list of strings.

# Python OS Object Method - provides methods to process files as well as directories.


# os.access(path, mode) Use the real uid/gid to test for access to path.

# os.chdir(path) Change the current working directory to path

# os.chflags(path, flags) Set the flags of path to the numeric flags.

# os.chmod(path, mode) Change the mode of path to the numeric mode.

# os.chown(path, uid, gid) Change the owner and group id of path to the numeric uid and gid.

# os.chroot(path) Change the root directory of the current process to path.

# os.close(fd) Close file descriptor fd.

# os.dup(fd) Return a duplicate of file descriptor fd.


# os.getcwd() Return a string representing the current working directory.

# os.open(file, flags[, mode]) Open the file file and set various flags according to flags and possibly its mode according to mode.

# os.remove(path) Remove the file path.

# os.rename(src, dst) Rename the file or directory src to dst.

# os.renames(old, new) Recursive directory or file renaming function.

# os.rmdir(path) Remove the directory path

# os.unlink(path) Remove the file path.

# os.write(fd, str) Write the string str to file descriptor fd. Return the number of bytes actually written.


# Additional Pyhton OS Module functions: http://www.tutorialspoint.com/python/os_file_methods.htm


# Python Exceptions Handling

# Exception Handling and Assertions are two methods available to handle unexpected error and add debugging capabilities


# KeyboardInterrupt: Raised when the user interrupts program execution, usually by pressing Ctrl+c.

# http://www.tutorialspoint.com/python/python_exceptions.htm

# Details on Python Exception Handling and Assertions are at above link

# Assertion in Python: assertion is a sanity-check that you can turn on or turn off when you are done with your testing of the program.

# Assertions are often put at beginning of function to check for valid input and after a function call to verify for valid output


# assert Expression[, Arguments]  syntax for assert


# If the assertion fails, Python uses ArgumentExpression as the argument for the AssertionError.

# Exception exemplifies a Python object that represents an error.

# Python must either fix the exception right away or python script terminates and quits

# A "try:" block followed  by "except" statements and ended by "else:" statements can be used to surround code that may be suspicious

try :
	
	fl = open("testfile", "w")
	
	fl.write("This is a sample file for exception handling.")

except IOError:
	
	print("Error: can\'t find file or read data")

else:

	print("Written content in the file with no issues")

	fl.close()

	
45

Written content in the file with no issues

fl = open("testfile", "r")

fl.read()

'This is a sample file for exception handling.'


# following example attempts to open a file to which user does not have access permission

try:

	tx = open("testfile", "r")

	tx.write("This is the sample file for exception handling.")

except IOError:


	print("Error: can\'t find file or read data")

else:

	print("Written content in the file with no issues"ArithmeticError)
	
SyntaxError: invalid syntax

try:

	tx = open("testfile", "r")

	tx.write("This is the sample file for exception handling.")

except IOError:

	print("Error: can\'t find file or read data")

else:

	print("Written content in the file with no issues")

	
Error: can't find file or read data

# example of using except statement with no exceptions defined:

# best practice is to do a try - except statement that indicates the root cause of the problem that may come up

# except Clause with Multiple Exceptions

# try:

 #  You do your operations here;

   ......................

# except(Exception1[, Exception2[,...ExceptionN]]]):

  #  If there is any exception from the given exception list, 

  #  then execute this block.


# try-finally clause: finally block is a location to put any code that must execute, whether the try-block raised an exception or not

# try:

#   You do your operations here;

# try-finally clause example

try:

	tp = open("sampletxt", "w")

	tp.write("This is a sample file for exception handling.")

finally:

	print("Error: can\'t find file or read data")

	
45

Error: can't find file or read data


try:

	br = open("testfile", "w")

	try:

		br.write("This my test file for exception handling.")

	finally:

		print("Going to close the file")

		br.close()

except IOError:

	print("Error: can\'t find file or read data")

	
41

Going to close the file

# providing an argument of an exception

# try:

# 	You do your operations here;

# exception ExceptionType, Argument:

# You can print value of Argument here...

# example below of single exception:

# def temp_convert(var):

   
#  Call above function here.

var = 10

def temp_convert(var):

	try:

		return int(var)

	except (ValueError, Argument):

		print("The argument does not contain numbers\n", Argument)

		

# raising an exception: raise [Exception [, args [, traceback]]]

# def functionName( level ):

def functionName( level):

	if level  < 1:

		raise ("Invalid level", level)

	# the code below this would not be executed

	# if we raise the exception

# to catch exception one needs to use an "except" clause that refers to the sample exception which is either a class object or simple string

# try:

#	Business Logic here...

# except "Invalid level":

#	Exception handling here...

# else:

# 	Rest of the code here...

# creating own new exeption

class Networkerror(RuntimeError): # an exception related to RuntimeError

	def _init_(self, arg):

		self.args = arg

# Python - Object Oriented Programming

# There several key components in Object Oriented Programming to be detailed below

# Components include: class, class variable, data member, function overloading, instance variable, inheritance, instantiation, method, object, operator overloading

# Creating a class

# syntax

# class ClassName:

#	'Optional class documentation string'

# 	class_suite

# access documentation string via ClassName._doc_

# class_suite: includes all component statements defining class members, data attributes, and functions

class Employee: # In this example class_name is 'Employee'

	'Common base class for all employees' # documentation string

	empCount = 0

	
def _init

# Python Objected Oriented Programming

class Employee:

	'Common base class for all employees'

	empCount = 0

	
def _init_(self, name, salaray):

	self.name = name

	self.salary = salary

	Employee.empCount += 1

	
def displayCont(self):

	print("Total Employee %d" % Employee.empCount)

	
def displayEmployee(self):

	print("Name : ", self.name ," Salary: ", self.salary)

def _init_(self, name, salary):

	self.name = name

	self.salary = salary

	Employee.empCount += 1

	
print(_init_)

<function _init_ at 0x02ADBF60>

def _init_(self, name, salary):

	self.name = "Ben"

	self.salary = "150k"

class Employee:

   'Common base class for all employees'

   empCount = 0

   def __init__(self, name, salary):

      self.name = name

      self.salary = salary

      Employee.empCount += 1
   
   def displayCount(self):

     print "Total Employee %d" % Employee.empCount

   def displayEmployee(self):

      print "Name : ", self.name,  ", Salary: ", self.salary

"This would create first object of Employee class"

emp1 = Employee("Zara", 2000)

"This would create second object of Employee class"

emp2 = Employee("Manni", 5000)

emp1.displayEmployee()

emp2.displayEmployee()

class Employee:

   'Common base class for all employees'

   empCount = 0

   def __init__(self, name, salary):

      self.name = name

      self.salary = salary

      Employee.empCount += 1
   
   def displayCount(self):

     print ("Total Employee %d" % Employee.empCount)

   def displayEmployee(self):

      print ("Name : ", self.name,  " Salary: ", self.salary)

"This would create first object of Employee class"

emp1 = Employee("Zara", 2000)

"This would create second object of Employee class"

emp2 = Employee("Manni", 5000)

emp1.displayEmployee()

emp2.displayEmployee()

class Employee:

   'Common base class for all employees'

   empCount = 0

   def __init__(self, name, salary):

      self.name = name

      self.salary = salary

      Employee.empCount += 1
   
   def displayCount(self):

     print ("Total Employee %d" % Employee.empCount)

   def displayEmployee(self):

      print ("Name : ", self.name,  " Salary: ", self.salary)
    
"This would create first object of Employee class"

emp1 = Employee("Zara", 2000)

"This would create second object of Employee class"

emp2 = Employee("Manni", 5000)

emp1.displayEmployee()

emp2.displayEmployee()

# "This would create first object of Employee class"

emp1 = Employee("Zara", 2000)

# "This would create second object of Employee class"

emp2 = Employee("Manni", 5000)

emp1.displayEmployee()

Name :  Zara  Salary:  2000

emp2.displayEmployee()

Name :  Manni  Salary:  5000

print ("Total Employee %d" % Employee.empCount)

Total Employee 2


emp1.age = 7 # Adding an 'age' attribute to emp1 of class

emp1.displayEmployee()

Name :  Zara  Salary:  2000

print(emp1.age)

7

emp1.age = 8 # modifying 'age' attribute in emp1 of class

print(emp1.age)

8

del emp1.age # deleting 'age' attribute from emp1 of class

hasattr(emp1, 'age') # returns true if 'age' attribute exists

False

emp1.age = 17 # Adding an 'age' attribute to emp1 of class

getattr(emp1, 'age') # returns value of 'age' attribute

17

hasattr(emp1, 'age')    # Returns true if 'age' attribute exists

True

setattr(emp1, 'age', 13) # set attribute 'age' at 13

getattr(emp1, 'age') # returns value of 'age' attribute

13

delattr(emp1, 'age') # deletes sttribute 'age'

hasattr(emp1, 'age')  # verify 'age' attribute deletion

False

# all Python classes have some of same built-in attributes accessible via dot operator

# _dict_ - dictionary containing the class's name space

# _doc_ - class documentation string or none, if it has been defined

# _name_ - name of class

# _module_ - This is the module name in which the class is defined. The value is _main_ in interactive mode

# _bases_ possibly empty tuple containing base classes, in order of their occurrence in base class list

class Employee:

	'Common base class for all employees'

	empCount = 0


def _init_(self, name, salary):

	self.name = name

	self.salary = salary

	Employee.empCount += 1

	
def displayCount(self):

	print("Total Employee %d" % Employee.empCount)

	
def displayEmployee(self):

	print("Name : ", self.name, "Salary: ", self.salary)

	
print ("Employee.__doc__:", Employee.__doc__)

Employee.__doc__: Common base class for all employees

print ("Employee.__name__:", Employee.__name__)

Employee.__name__: Employee

print ("Employee.__module__:", Employee.__module__)

Employee.__module__: __main__

print ("Employee.__bases__:", Employee.__bases__)

Employee.__bases__: (<class 'object'>,)

print ("Employee.__dict__:", Employee.__dict__)

Employee.__dict__: {'__module__': '__main__', '__doc__': 'Common base class for all employees', '__dict__': <attribute '__dict__' of 'Employee' objects>, 'empCount': 0, '__weakref__': <attribute '__weakref__' of 'Employee' objects>}

# "The process by which Python periodically reclaims blocks of memory that no longer are in use is termed Garbage Collection."

# http://www.tutorialspoint.com/python/python_classes_objects.htm

d = 24 # create object <24>

e = d # increase ref. count of <24>

f = [e] # increase ref. count of <24>

del d # decrease ref. count of <24>

e = 48 # decrease ref. count of <24>

f[0] = -14 # decrease ref. count of <24>

# __del__() - destructor is special method that prints class name of instance that is about to be destroyed

class Point: # defining class 'Point'

	def __init(self, x=0, y=0):

		self.x = x

		self.y = y

	def __del__(self):

		class_name = self.__class__.__name__

		print(class_name, "destroyed")

		
pt1 = Point()

pt2=pt1

pt3=pt1

print (id(pt1), id(pt2), id(pt3)) # prints ids of the objects

45040624 45040624 45040624

del pt1

del pt2

del pt3

Point destroyed

# Class inheritance: allows a new class to adopt the attributes in an existing class; put parent class name in parentheses after the name of child class name

# class SubClassName (ParentClass1 [, ParentClass2, ...]):

#	'Optional class documentation string'

#	class_suite

class Parent: # define parent class

	parentAttr = 0

	def __init__(self):

		print("Calling parent constructor")

		
def parentMethod(self):

	print('Calling parent method')

	
def setAttr(self, attr):

	Parent.parentAttr = attr

	
def getAttr(self):

	print("Parent attribute : ", Parent.parentAttr)

	
class Child(Parent): #define child class

	def __init_(self):

		print("Calling child constructor")

		
def childMethod(self):

	print('Calling child method')

	
c = Child() # instance of child

Calling parent constructor

  
def ChildMethod(self):

	print('Calling child method')

	
c = Child()

Calling parent constructor

self = "team"

Child.__init__(self)

Calling parent constructor

c = Child()

Calling parent constructor

c = childMethod(self)

Calling child method

c = parentMethod(self)

Calling parent method

c = setAttr(self, attr)

print(c)

None

c = getAttr(self)

Parent attribute :  200


# can derive a new class from more than one parent class

# class A:  define Class A

# class B:  define Class B

# class C (A, B):  subclass of A and B

# issubclass(sub, sup) returns true if given subclass sub is a subclass of superclass sup

# isinstance(obj, Class) returns true if obj is an instance of class Class or is an instance of subclass of Class

# can override methods from parent class methods in case want different abilities in new subclass

class Momma: # define parent class

	def myMethod(me):

		print("Calling parent method")

		
class Mini(Parent): # define child class

	def myMethod(me):

		print("Calling child method")

		
c = Mini() # instance of child

Calling parent constructor

self = 'group'

me = 'team'

c = Mini.myMethod(me)

Calling child method


# Base Overloading Methods - several generic functionality that can override in a class

# __init__ ( self [,args...] ) Constructor (with any optional arguments)

# __del__( self ) Destructor, deletes an object ex. del obj

# __repr__( self ) Evaluatable string representation ex. repr(obj)

# __str__( self ) Printable string representation ex. str(obj)

# 	__cmp__ ( self, x ) Object comparison ex. cmp(obj, x

