#1 Waypoint: Comment your JavaScript Code
Comments are lines of code that your computer will intentionally ignore. Comments are a great way to leave notes to yourself and to other people who will later need to figure out what it does.

Let's take a look at the two ways you can write comments in JavaScript.

The double-slash comment will comment out the remainder of the text on the current line:

`// This is a comment.`

The slash-star-star-slash comment will comment out everything between the /* and the */ characters:

`/* This is also a comment */`

Try creating one of each.

And one more thing you need to notice. Starting at this waypoint in JavaScript related challenges (except AngularJS, all Ziplines, Git, Node.js and Express.js, MongoDB and Full Stack JavaScript Projects) you can see contents of assert() functions (in some challenges except(), assert.equal() and so on) which are used to test your code. It's part of these challenges that you are able to see the tests that are running against your code.

#2 Waypoint: Understand Boolean Values
In computer science, data structures are things that hold data. JavaScript has seven of these. For example, the `Number` data structure holds numbers.

Let's learn about the most basic data structure of all: the `Boolean`. Booleans can only hold the value of either true or false. They are basically little on-off switches.

Let's modify our welcomeToBooleansfunction so that it will return `trueinstead` of `falsewhen` the run button is clicked.

#3 Waypoint: Declare JavaScript Variables
When we store data in a data structure, we call it a variable. These variables are no different from the x and y variables you use in math.

Let's create our first variable and call it "myName".

You'll notice that in myName, we didn't use a space, and that the "N" is capitalized. JavaScript variables are written in camel case. An example of camel case is: camelCase.

Now, use the `var` keyword to create a variable called myName. Set its value to your name, in double quotes.

Look at the ourName example if you get stuck.

#4 Waypoint: Declare String Variables
In the previous challenge, we used the code var myName = "your name". This is what we call a String variable. It is nothing more than a "string" of characters. JavaScript strings are always wrapped in quotes.

Now let's create two new string variables: myFirstNameand myLastName and assign them the values of your first and last name, respectively.

#5 Waypoint: Check the Length Property of a String Variable
data structures have properties. For example, strings have a property called `.length` that will tell you how many characters are in the string.

For example, if we created a variable `var firstName = "Charles"`, we could find out how long the string "Charles" is by using the `firstName.length property`.

Use the `.length` property to count the number of characters in the lastName variable.

#6 Bracket notation is a way to get a character at a specific index within a string.

Computers don't start counting at 1 like humans do. They start at 0.

For example, the character at index 0 in the word "Charles" is "C". So if var firstName = "Charles", you can get the value of the first letter of the string by using firstName[0].

Use bracket notation to find the first character in the firstLetterOfLastName variable.

Try looking at the firstLetterOfFirstName variable declaration if you get stuck.

#7 Waypoint: Use Bracket Notation to Find the Nth Character in a String
You can also use bracket Notationto get the character at other positions within a string.

Remember that computers start counting at 0, so the first character is actually the zeroth character.

Let's try to set thirdLetterOfLastNameto equal the third letter of the lastName variable.

Try looking at the secondLetterOfFirstName variable declaration if you get stuck.

#8 Waypoint: Use Bracket Notation to Find the Last Character in a String
In order to get the last letter of a string, you can subtract one from the string's length.

For example, if var firstName = "Charles", you can get the value of the last letter of the string by using `firstName[firstName.length - 1]`.

Use bracket notation to find the last character in the lastName variable.

Try looking at the lastLetterOfFirstName variable declaration if you get stuck.

#9 Waypoint: Use Bracket Notation to Find the NthtoLast Character in a String
In order to get the last letter of a string, you can subtract one from the string's length.

For example, you can get the value of the third-to-last letter of the var firstName = "Charles" string by using `firstName[firstName.length - 3]`.

Use bracket notation to find the second-to-last character in the lastName string.

Try looking at the lastLetterOfLastName variable declaration if you get stuck.

#10 Waypoint: Add Two Numbers with JavaScript
Let's try to add two numbers using JavaScript.

JavaScript uses the `+` symbol for addition.

Replace the 0 with the correct number so you can get the result mentioned in the comment.

#11 Waypoint: Subtract One Number from Another with JavaScript
We can also subtract one number from another.

JavaScript uses use the `-` symbol for subtraction.

Replace the 0 with the correct number so you can get the result mentioned in the comment.

#12 Waypoint: Multiply Two Numbers with JavaScript
We can also multiply one number by another.

JavaScript uses use the `*` symbol for multiplication.

Replace the 0 with the correct number so you can get the result mentioned in the comment.
