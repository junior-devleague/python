# Introduction to Python Class Briefing

## Week 1

### Class Recap 4/4/18
Format of class was as follows:
- Instructors introduced themselves
- Talked about what Jr. DevLeague is, where and what we teach
- Students introduced themselves
- Overview of what they will be learning
  - Explained Pythong
  - Explained Processing
  - Overview of a Raspberry Pi
- Overview of Slack
  - Slack rules
  - How to use `@` for mentions, channel, here
  - Direct Messages
  - Passed out code of conduct
- Overview of REPL
- Ice Breaker/Getting To Know Eachother
  - Students were told to sit next to someone they don't know, and were then paired together
  - Students introduced themselves to their partner
  - Students then discussed if they could program anything in the world what would they program
  - Students shared with the class what their partner wants to program

## Week 2

### Class Recap 4/9/18
Format of class was as follows:
- What is computer programming?
  - A computer program is a set of instructions that causes a computer to perform tasks
  - It’s a set of commands that tell the computer what to do
  - Software is a collection of computer programs
- Fundamentals of Computer Programming
  - Syntax
  - Data
  - Control Flow
  - Functions
- Intro to Python Variables
  - What is a variable?
  - In programming, variables describe a place to store information.
  - You can store numbers, text, and lists of numbers and text
- Whiteboard Examples
- Variables & Data Types Live Code
- Naming conventions
  - Variable names can include numbers or letters, but should always start with a letter
  - Python uses snake case for separating each word using underscores
    - Example: `treasure_chest = 'gold'`
- Datatypes
  - Text
    - The text data type can be identified by quotation marks
    - Text should be wrapped in either single or double quotes
    - Numbers wrapped in quotes are still text
  - Integeres
    - Integers are written without quotes
    - Integers can be whole, negative, or include decimals but NOT commas
  - List
    - Lists are contained within square brackets
    - Each item should be separated by a comma
    - Lists can contain text, numbers, and other lists
  - Displaying values on a console or terminal with print()
    - print() gives us immediate feedback on our code
    - We can easily see the values of our variables with print()
- Math operators
  - Add +, Subtract - , Multiply * , Divide /
  - Order of operation rules still apply in programming where multiplication and division will be executed before addition and subtraction.
  - To control the order of operations we wrap our calculation in parenthesis.
```Example:
5  + 30 * 20 = 605
(5 + 30) * 20 = 700
```
- Variables Activity & Assignment
  - Search & Conquer Variables: https://github.com/junior-devleague/search_and_conquer_variables

### Class Recap 4/11/18

Format of class was as follows:

* Introduction to Raspberry Pi
  * What is a Raspberry Pi
    * Anatomy of a Raspberry Pi
      * Types of cables needed
        * Power Supply
        * HDMI
        * HDMI
        * Keyboard
        * Mouse
        * External Monitor
        * Wifi or ethernet cable
* Installation
  * Installed Raspbian on 8 Pi's
* Intro to Terminal/CLI
  * What is a Terminal/CLI
  * How to navigate through the file system
  * Basic CLI commands
    * cd
    * cd ..
    * li
    * mkdir
    * touch
* Variables and data types review
  * Have students call out variables of different types
  * Livecode the examples
  * Make mistakes and have students debug
  
## Week 3

### Class Recap 4/16/18

Format of class was as follows:

* Introduction to functions
  * What is a function
  * How to declare a function
  * Syntax
  * Components
  * Why we use functions
* Livecode example
  * Create functions with the class
  * Have them explain components
  * Guess return values
* Funcion exercise
  * Using all operators we went over`(+ - / *)`
  * Create functions
  * Go around class and help debug and explain

### Class Recap 4/18/18

Format of class was as follows:

* Function review
  * What is a function
  * The componenets of a function
  * Syntax of a function
  * Why we use functions
* Function exercise
  * In groups of two or three
  * All solutions should be done in multiple functions
  * Calculate tax on a single item and return that value
    * Did this as a class
  * Subtract that value from a wallet variable
  * Convert the subtract function to take into accoutn multiple items
  * Went around the room to help groups debug, and answer questions
* Whiteboarding example
  * Gave an example of whiteboarding using the function exercise
  * Had two volunteers whiteboard together
  
## Week 4

### Class Recap 4/24/18

Format of class was as follows:
- What are conditions?
  - A conditional says “If something is true, do this… Otherwise, do that”
  - Programs often ask us questions, and then it runs some code based on our answers
      - Example:
        - Are you 13 years or older?
        - If yes, you can play the game
        - If no, ask parents for permission
- Whiteboard Real Life Examples
  - Asked students what happens to them if they don’t finish their homework
  - Asked students how does a game usually determine who a winner is in a 2 person match
  - Asked students what happens when they eat 10 pounds of shredded cheese in one sitting
- Live Code Examples ( if statement only first )
  - If statements
    - An if statement is used to execute a piece of code if something is true
    - The piece of code will only run if the condition is true
  - Structure of an if statement
```
if (condition statement):
    // code to be executed if statement is true
```
- Show students how to turn examples on whiteboard into real python code
```
is_homework_done = False
if (is_homework_done == False):
  print(‘do something’)

# game example
player1_score = 100
player2_score = 99
if (player1_score > player2_score):
  print(‘player1 is the winner’)

# shredded cheese example
shredded_cheese_eaten_in_pounds = 10
if (shredded_cheese_eaten_in_pounds >= 10):
  print(‘stomach ache for days’)
```
- If/else statements
  - Else is added to statement if the condition in the if statement is false
    - Example: IF you finish your homework, you can have ice cream, but if you don’t finish your homework, you don’t get ice cream.

- Structure of an if/else statement
```
if (condition statement):
    // code to be executed if statement is true
else:
    // code to be executed if statement is false

# homework example with else statement
is_homework_done = False
if (is_homework_done == False):
  print(‘no ice cream for you’)
else:
  print(‘you can have ice cream’)

# game example with else statement
player1_score = 100
player2_score = 99
if (player1_score > player2_score):
  print(‘player1 is the winner’)
else:
  print(‘player2 is the winner’)

# shredded cheese example with else statement
shredded_cheese_eaten_in_pounds = 10
if (shredded_cheese_eaten_in_pounds >= 10):
  print(‘stomach ache for days’)
else:
  print(‘no stomach ache for you’)
```

Assignment:
- conditional-friendship: https://github.com/junior-devleague/conditional-friendship
