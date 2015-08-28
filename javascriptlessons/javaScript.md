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

#13 Waypoint: Divide One Number by Another with JavaScript
We can also divide one number by another.

JavaScript uses use the `/` symbol for division.

Replace the 0 with the correct number so you can get the result mentioned in the comment.

#14 Waypoint: Create Decimal Numbers with JavaScript
JavaScript number variables can also have decimals.

Let's create a variable `myDecimal` and give it a decimal value.

# 15 Waypoint: Perform Arithmetic Operations on Decimals with JavaScript
In JavaScript, you can also perform calculations with decimal numbers, just like whole numbers.

Replace the 0.0 with the correct number so that you get the result mentioned in the comments.

#16 Waypoint: Store Multiple Values in one Variable using JavaScript Arrays
With JavaScript array variables, we can store several pieces of data in one place.

You start an array declaration with an opening bracket, end it with a closing bracket, and put a comma between each entry, like this: `var sandwich = ["peanut butter", "jelly", "bread"]`.

Now let's create a new array called myArray that contains both a string and a number.

Refer to the comments if you get stuck.

# 17 Waypoint: Nest one Array within Another Array
You can also nest arrays within other arrays, like this: [["Bulls", 43]].

Let's now go create a nested array called myArray.

#18 Waypoint: Access Array Data with Indexes
We can access the data inside arrays using indexes.

Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array.

For example:

```
var array = [1,2,3];

array[0]; //equals 1

var data = array[1];
```

Create a variable called myData and set it to equal the first value of myArray.

#19 Waypoint: Modify Array Data With Indexes
We can also modify the data stored in arrays by using indexes.

For example:

```
var ourArray = [3,2,1];

ourArray[0] = 1; // equals [1,2,1]
```

Now modify the data stored at index 0 of myArray to the value of 3.

#20 Waypoint: Manipulate Arrays With pop
Another way to change the data in an array is with the `.pop()` function.

.pop()is used to "pop" a value off of the end of an array. We can retrieve this value by performing `pop()` in a variable declaration.

Any type of variable can be "popped" off of an array.

Use the `.pop()` function to remove the last item from myArray.

#21 Waypoint: Manipulate Arrays With push
Not only can you `pop()` data off of the end of an array, you can also `push()` data onto the end of an array.

Take the myArray array and `push()` this value to the end of it: ["dog", 3].

#22 Waypoint: Manipulate Arrays With shift
`pop()` always removes the last element of an array. What if you want to remove the first? That's where `.shift()` comes in.

#23 Waypoint: Manipulate Arrays With unshift
Now that we've learned how to shiftthings from the start of the array, we need to learn how to `unshift` stuff back to the start

Let's take the code we had last time and unshiftthis value to the start: "Paul"

#24 Waypoint: Write Reusable JavaScript with Functions
In JavaScript, we can divide up our code into reusable parts called functions.

Here's an example of a function:

```
function functionName (a, b) {

  return(a + b);

}
```
We can "call" our function like this: `functionName();`, and it will run and return its return value to us.

Create and call a function called myFunction that returns the sum of a and b.

Take the myArray array and shift() the first value off of it.
