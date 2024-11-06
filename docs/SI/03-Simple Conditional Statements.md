# Simple Conditional Statements

## Selection - If, Explanation

Programs have to make decisions.

You have seen how these decisions can be represented on a flowchart (notice the diamond shapes with yes/no decisions).

In National 5, you will often be asked to follow a design that has these decisions. You will implement the decisions in Python with if statements.

## If statements

Your programs will often react to something input by the user.

In this example, the user is asked to enter a password. If they enter “hello123”, access is granted:

!!! example
	```Python
	# Ask the user to enter a password
	passwd = input("Please enter the password")
	
	# Is access granted?
	if passwd == “hello123”:
		print("Access granted")
	```

The if statement always starts with the word if, followed by a condition. A condition checks that something is equal to, greater than or less than something else. In this case, it checks if passwd (what the user entered) is equal to the string “hello123”.

We use indentation for any code that we want to be inside the if statement (this means we tab it in). Notice that the print statement is tabbed in slightly from the left. This means that it only happens if the if statement above it is true. We could have multiple lines of code inside the if statement.
The if statement always ends in a colon :

== Note the use of the double-equals ==. We use two equals signs when checking for equality in an if statement. We can use the == signs for testing if any variable matches any other data. When our data is a number (whether it is an integer or a real number), we can see if it is less than or greater than another number ==

| Symbols     | Description                                                     |
| ----------- | ----------------------------------------------------------------|
| `==`        | Equal to, e.g. 5 == 5, score == 12 or faveSubject == "Computing"|
| `<`         | Less than, e.g. 40 and 62 are both < 99                         |
| `>`         | Greater than, e.g. 50.4 and 85.1 are both > 10.8                |
| `<=`        | Less than or equal to, e.g. 22 and 70 are both <= 70            |
| `>=`        | Greater than or equal to, e.g. 100 and 105 are both >= 100      |


**In computing however, we usually give them a longer (more meaningful) name, such as:**

!!! example
	```Python
	age = 15
	name = "Bob"
	email = "bob@gmail.com"
	```
	
## Python Variable Naming Rules

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
- A variable name cannot be any of the **Python keywords**.

and although this one is not a rule....

- It is important to use **meaningful** or **sensible** variable names. 

## Types of Variables

In programming variables have a particular type and for National 5 there are five data types that you need to know:

| Data Type   | Description                                  |
| :---------: | :-------------------------------------------:|
| Integer     | Whole number: 12, -50, 100                   |
| Real number | With a decimal point: 22.5, 0.001            |
| String      | Words and symbols: hello, abc123             |
| Character   | A single letter, digit or symbol: a, Z, $, # |
| Boolean     | True (1) or False (0)                        |

!!! warning

    Once a variable has been set up with a particular type, you can only assign it data of that type.


!!! example
	```Python
	# This is an integer
	myage = int(15)

	# This is a real number
	price = float(0.99)

	# This is a string
	faveSubject = str("Computing")

	# This is a character
	firstInitial = char("F")

	# This is a Boolean
	isStudent = bool(1)
	```

## Calculations

Python programs will often carry out calculations with operators. The result is usually stored in a variable:

!!! example
```Python
num1 = 5
num2 = 7
sum = num1 + num2
```

You can use the following operators:

!!! example
	```Python
	# Three variables
	num1 = 5
	num2 = 7
	sum = 0.0

	# Addition
	sum = num1 + num2

	# Subtraction
	sum = num1 - num2

	# Division
	sum = num1 / num2

	# Multiplication
	sum = num1 * num2

	# Raise to a power
	sum = num1 ** num2

	#Note that “raising to the power” means, for example, num1**num2. 

	#To square or cube a number, you would say:
	square = num1 ** 2
	cube = num1 ** 3
	```

## String Concatenation

String concatenation is the term used when **joining** two strings.

!!! example
	```Python
	word1 = “Hello”
	word2 = “World”

	sentence = word1 + word2
	```

!!! tip

    The example above doesn’t include a space, you would have to add a space to the end of **“Hello”** or the beginning of **“World”**. 


