# python
my notes from my 5 hours i spent learing python 3 on codecademy, super dope language and really fun :)

# notes
coding notes from learning python on CA:
1. comments
- start a line with # and anything after that the computer ignores
- these are called comments, give context or instructions
- documentation is important in programming
2. print
- self explainitory, prints what you tell it
- print("*ur message*")
- dont forget quotation marks ""
3. strings
- strings are text within the code
- can use ' or ", doesnt matter just be consistant
4. variables
- bank (if you will) that can store a value
- e.g. message_string = "sup homie"
# prints "sup homie"
print(message_string)
# refers to the value which is storing the value (string)
- cannot include spaces, symbols, special letters BUT can include numbers but only after the first letter. for example: this_is_ok_69 = "LOL"
- if the context of the program changes, insteading of changing all the strings you just need to change the variable which is holding the value (string) since all your prints are refering to the variable
- Q&A: 
***************************************************************************
# We've defined the variable "meal" here to the name of the food we ate for breakfast!
meal = "An english muffin"

# Printing out breakfast
print("Breakfast:")
print(meal)

# Now update meal to be lunch!
meal = "Sandwich"

# Printing out lunch
print("Lunch:")
print(meal)

# Now update "meal" to be dinner

meal = "Chicken"

# Printing out dinner
print("Dinner:")
print(meal)
***************************************************************************
5. errors
- programs will attempt to indentify, understand and explain mistakes in their code/program
- python 3 refers to these mistakes as "errors"
- they will point out where this mistake was made with a "^" symbol
- there might be unexpected errors withtin your code that was not picked up and they are called "bugs"
- the process of updating the program to get rid of the bugs is called "debugging"
- two common errors that occur when writing python 3 are "NameError" and "SyntaxError"
- a NameError happens when python sees a word that isnt intimate with the program. a bit of code that looks like a variable but was never defined. you probably misspelt the word or something
- a SyntaxError means that there is something wrong with your program due to the way it was written. much like a calculator SyntaxError its probably because you have punctuation that does not belong, missing parenthesis (this thing thats hugging this text <3) or a command where it is not expected or a missing parenthesis can all cause a SyntaxError
- Q&A:
***************************************************************************
print('This message has mismatched quote marks!")
print(Abracadabra)
***************************************************************************- you may ask: "whats wrong with this homie?". well, the first line is a SyntaxError because it opens and closes with different quotation marks. BE CONSISTANT HOMIE. the second line is a NameError because it doesnt even have quotation marks man.
- FIXED
***************************************************************************
print("This message has mismatched quote marks!")
print("Abracadabra")
***************************************************************************
6. numbers
- computers can understand more than string of text
- there are multiple ways of storing numbers, it all depends of the purpose for the number you're storing
- these consist of intergets (int) and floating-point number (float)
- an interger or int is a whole number, NO DECIMAL POINTZ.
- contains all count numbers: 1,2,3... as well as their negative halfs (negatives) and the number 0
- if u were finna count the number of books on a shelf, number of kids in a class or number of songs in my fire af playlist you would most likely use an int (interger)
- a floating-point number (LLOOOOOL THAT NAME) or a float is a decimal number
- can be used to represent fraction tingz and exact measurements
- if u were measuing the length of your room door or how tall post malone is then you would use a float (floating-point number)
- can be used in programs *migos: STRAIGHT UP!* or can be assigned to variables
- REFRENCE:
***************************************************************************
an_int = 2
a_float = 2.1

print(an_int + 3)
# prints 5
***************************************************************************
- here we defined the int and float as variables
- we printed out the sum of the int variable plus 3
- the 3 here is called a literal which means its legit just the number 3 with no variable assigned to it
- Q&A:
***************************************************************************
1. A recent movie-going experience has you excited to publish a review. You rush out of the cinema and hastily begin programming to create your movie-review website: The Big Screen’s Greatest Scenes Decided By A Machine.

Create the following variables and assign integer numbers to them: release_year and runtime.

# Define the release and runtime integer variables below:

release_year = 2005
runtime = 2

2. Now, create the variable rating_out_of_10 and assign it a float number between one and ten.

# Define the rating_out_of_10 float variable below: 

rating_out_of_10 = 8.5
***************************************************************************
7. calculations
- btw, computers are maths gods lol
- python can do addition, subtraction, multiplication and division with + 4 ad, - 4 sub, * 4 times and / 4 divide
- EXAMPLEEE
***************************************************************************# Prints "500"
print(573 - 74 + 1)

# Prints "50"
print(25 * 2)

# Prints "2.0"
print(10 / 5)
***************************************************************************
- when division is peformed, it is presented as a float even if the answer is a whole number
- this is because python automatically converts all ints to floats before peforming the equation
- python 2.7 and earlier dont do this conversion (python 3 gang for lyfe). it was always round down to the nearest int
- division has its own error which is known as ZeroDivisionError. it will occur when trying to divide by 0
- maths in python follow bodmas (order of operations)
- don't use quotation marks cos its not a string, its an EQUATION!1!!
8. changing numbers
- use variables and change the value in the variable to change numbers
- you can only update a variable using the = sign
- Q&A:
***************************************************************************
1. You’ve decided to get into quilting! To calculate the number of squares you’ll need for your first quilt let’s create two variables: quilt_width and quilt_length. Let’s make this first quilt 8 squares wide and 12 squares long. Print out the number of squares you’ll need to create the quilt!
//

quilt_width = 8
quilt_length = 12

# prints 96
print(quilt_width * quilt_length)

//
2. It turns out that quilt required a little more material than you have on hand! Let’s only make the quilt 8 squares long. How many squares will you need for this quilt instead?
//

quilt_width = 8
quilt_length = 8

# prints 64
print(quilt_width * quilt_length)

//
***************************************************************************
9. exponents
- python can do exponentiation (powers). 
- to achive powers, instead of using a single * for multiplication use ** for powers.
- EXAMPLE:
***************************************************************************
# 2 to the 10th power, or 1024
print(2 ** 10)

# 8 squared, or 64
print(8 ** 2)

# 9 * 9 * 9, 9 cubed, or 729
print(9 ** 3)

# We can even perform fractional exponents
# 4 to the half power, or 2
print(4 ** 0.5)
***************************************************************************
- "Here, we compute some simple exponents. We calculate 2 to the 10th power, 8 to the 2nd power, 9 to the 3rd power, and 4 to the 0.5th power." - mr/mrs(ITS 2019). codecademy
- Q&A:
***************************************************************************1. You really like how the square quilts from last exercise came out, and decide that all quilts that you make will be square from now on.
Using the exponent operator, print out how many squares you’ll need for a 6x6 quilt, a 7x7 quilt, and an 8x8 quilt.
//

# Calculation of squares for:
# 6x6 quilt
print(6 ** 2)
# 7x7 quilt
print(7 ** 2)
# 8x8 quilt
print(8 ** 2)

# prints 36 49 and 64

//

2.Your 6x6 quilts have taken off so well, 6 people have each requested 6 quilts. Print out how many tiles you would need to make 6 quilts apiece for 6 people.
//

# How many squares for 6 people to have 6 quilts each that are 6x6?
print(6 ** 4)

//
***************************************************************************
10. modulo
- so python got this dope thing where theres a companion to the division operator called modulo.
- its sign is a %p%e%r%c%e%n%t%a%g%e% symbol
- gives the remainder of the result calculated by division
- if the number is divisable, the modulato will be 0
- REFRENCE:
***************************************************************************# Prints 4 because 29 / 5 is 5 with a remainder of 4
print(29 % 5)

# Prints 2 because 32 / 3 is 10 with a remainder of 2
print(32 % 3)

# Modulo by 2 returns 0 for even numbers and 1 for odd numbers
# Prints 0
print(44 % 2)
***************************************************************************
- "Here, we use the modulo operator to find the remainder of division operations. We see that 29 % 5 equals 4, 32 % 3 equals 2, and 44 % 2 equals 0." - the homie codecademy
Q&A:
***************************************************************************1. You’re trying to divide a group into four teams. All of you count off, and you get number 27.
Find out your team by computing 27 modulo 4. Save the value to my_team.
//

my_team = 27 % 4

print(my_team)

//
***************************************************************************
11. concatenation
- + doesnt just add numbers together, its also capable of adding two srtings 
- the action of adding two strings is called string concatenation
- if string concatenation is peformed, a new string is formed composed of the first string's value and second string's value (no space is put in-between)
- EXAMPLE:
***************************************************************************greeting_text = "Hey there!"
question_text = "How are you doing?"
full_text = greeting_text + question_text

# Prints "Hey there!How are you doing?"
print(full_text)
***************************************************************************
- we have made and defined our variables
- by using string concatenation we used the 3 strings we made and used the full_text variable and we then printed it to add both strings
- theres no space btw :( UNLESS!!! ---> (down lol)

full_text = greeting_text + " " + question_text

# Prints "Hey there! How are you doing?"
print(full_text)

//
- the str() function is used when you want to concatenate both a number and a string
- EXAMPLE:
***************************************************************************birthday_string = "I am "
age = 10
birthday_string_2 = " years old today!"

# Concatenating an integer with strings is possible if we turn the integer into a string first
full_birthday_string = birthday_string + str(age) + birthday_string_2

# Prints "I am 10 years old today!"
print(full_birthday_string)

# If we just want to print an integer 
# we can pass a variable as an argument to 
# print() regardless of whether 
# it is a string.

# This also prints "I am 10 years old today!"
print(birthday_string, age, birthday_string_2)
***************************************************************************
- the age string was a number not like the other variables that were normal text strings. str() helps concatenate it.
- Q&A: 
***************************************************************************1. Concatenate the strings and save the message they form in the variable message.
Now uncomment the print statement and run your code to see the result in the terminal!
//

string1 = "The wind, "
string2 = "which had hitherto carried us along with amazing rapidity, "
string3 = "sank at sunset to a light breeze; "
string4 = "the soft air just ruffled the water and "
string5 = "caused a pleasant motion among the trees as we approached the shore, "
string6 = "from which it wafted the most delightful scent of flowers and hay."

# Define message below:

message = string1 + string2 + string3 + string4 + string5 + string6 

#print(message)

print(message)

#prints the text, too lazy to copy and paste hehe
***************************************************************************
12. plus equals
- theres a shortcut when updating variables in python
- when there is a number stored in a variable and you want to add to the current value in the variable you can use the += (plus equals) operator.
- EXAMPLE:
***************************************************************************
# First we have a variable with a number saved
number_of_miles_hiked = 12

# Then we need to update that variable
# Let's say we hike another two miles today
number_of_miles_hiked += 2

# The new value is the old value
# Plus the number after the plus-equals
print(number_of_miles_hiked)
# Prints 14
***************************************************************************
- we keep the original value while adding 2. pretty much we add on to the total
- instead of recalculating, we keep a gran total homie
- Q&A:
***************************************************************************
1. We’re doing a little bit of online shopping and find a pair of new sneakers. Right before we check out, we spot a nice sweater and some fun books we also want to purchase!

Use the += operator to update the total_price to include the prices of nice_sweater and fun_books.

The prices (also included in the workspace) are:

new_sneakers = 50.00
nice_sweater = 39.00
fun_books = 20.00
//

total_price = 0

new_sneakers = 50.00

total_price += new_sneakers

nice_sweater = 39.00
fun_books = 20.00
# Update total_price here:

total_price += nice_sweater + fun_books 

print("The total price is", total_price)
***************************************************************************
14. multi-line strings
- python will give you a syntax error when a string takes up too many lines.
- the solution is use """3 quotations marks""" instead of "1"
- Q&A:
***************************************************************************
1.
Assign the string:

Stranger, if you passing meet me and desire to speak to me, why
  should you not speak to me?
And why should I not speak to you?
to the variable to_you.
//

# Assign the string here

to_you = """Stranger, if you passing meet me and desire to speak to me, why
  should you not speak to me?
And why should I not speak to you?"""

print(to_you)

//
***************************************************************************
15. WE DONE BROOOO
- PYTHON IS ACTUALLY SO COOL LOOOL
