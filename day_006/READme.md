##Getting Random Numbers using Dice :
We all know that for a regular 6-sided dice, the dice rolls are between 1 to 6 and also we know about the different data types like Int, Float, String, Double and Char etc. IntRange is also a data type, and it is used to represent a range of integer numbers from a starting to an end number.
For a regular 6-sided dice, we can use IntRange to assign the value from 1 to 6. We have to declare IntRange in the program as 1(starting Number).. followed by 6(Ending Number)
variable Name= (Starting Number)..(Ending Number)
random() is to generate and return a random number for a given range.
String formatting notation is used to see the number which is generated randomly (${randomNumber})

##Program to roll the Dice:
Creating Dice Class:
~Create a Dice class below the main function and add the sides of the dice
~Create an object instance of Dice in main function
~Assign the number from 1 to 6 and Using random() to get the random numbers

##Program to return the dice roll´s value:
~Assign the value of roll() method to a variable
~specify the data type in roll() function
~Use return statement to return the value
~Add Print statement to print the values
~Run the code to get the output

##Program to change the number of sides:
In roll() method, the size 1..6 can be changed to 1..sides, 
In main function, the sides is set to 20 and other lines in the program remains same. Run the program to get the output
