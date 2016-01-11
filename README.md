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
  File "C:\Users\brzmun\AppData\Local\Programs\Python\Python35-32\lib\idlelib\PyShell.py", line 1386, in readline
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
		if c/j is not : break
		
SyntaxError: invalid syntax
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
