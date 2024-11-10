# Pre-Defined Functions

## Explanation

Pre-defined functions are built-in to Python. This saves you “reinventing the wheel” each time you use them.

When you use a pre-defined function, you pass one or more parameters. 

__The parameter is the part in brackets.__

!!! example

	```python numlines="1"
		pi = round(3.14159265)
	```
There are three pre-defined functions that you must know for National 5: 

* Random
  
* Round

* Length

## Random Number

Something that is random is open to chance - like rolling dice, or tossing a coin.

Before we use a random number, we have to put this line at the top of the program:

!!! example

	```python numlines="1"
		# This program is going to use random numbers
		import random
	```

Random will always returns an integer (a whole number) and will only generate a random number that is between two parameters:

!!! example

	```python numlines="1"
		# Generate a random number from 1 to 6
		dice = random.randint(1, 6)
	```

The code above will generate a number that could be either 1, 2, 3, 4, 5 or 6.

Complete example:

!!! example "The Random Number Game"

	```python numlines="1"
 
		# Add the random module
		import random
		
		# Ask the user to enter a number
		guess = int(input("What is your guess?"))
		
		target = random.randint(1, 10)
		if guess == target:
			print("Well done, you guessed correctly.")
		else:
			print("Sorry, you guessed wrongly")
	```
		 
