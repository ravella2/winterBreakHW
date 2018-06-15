# weekend-js-1
Long_Weekend covering loops, functions, and datatypes


## Conceptual Questions

1. How do we assign a value to a variable? 
2. How do we change the value of a variable? 
3. How do we assign an existing variable to a new variable?

## Strings

1. Create a variable called `firstVariable`.
  - assign it the value of a string => `"Hello World"`
  - change the value of this variable to a number.
  - store the value of `firstVariable` into a new variable called `secondVariable` 
  - change the value of `secondVariable` to a string. 
  - What is the value of `firstVariable`?

2. Create a variable called `yourName` and set it equal to your name as a string.
  - Write an expression that takes the string "Hello, my name is " and the variable `yourName` so that it returns a new string with them concatenated. 
  
>ex: `Hello, my name is Jean Valjean`
  
## Booleans
- Using the provided variable definitions, replace the blanks with a mathematical or boolean operator that evaluates the expression to true. :wave:

```
  const a = 4;
  const b = 53;
  const c = 57;
  const d = 16;
  const e = 'Kevin';
```

-  a _ b;
-  c _ d;
-  'Name' ___ 'Name';
-  a _ b ___ c;
-  a _ a ___ d;
-  e ___ 'Kevin';
-  48 ___ '48';

...


## The Farm
1) Write code that will print out "mooooo" if the variable `animal` is equal to `cow`.

2) Change your code so that if the variable `animal` is anything other than a cow, your should print out "Hey! You're not a cow."

## Driver's Ed

1) Write a variable that will hold a person's age.

2) Write code that will print out "Here are the keys", if the age is 16 years or older.

3) Change your code so that if the age is younger than 16, a message will print "Sorry, you're too young."

## Just Loop It
1) Write code that will print out all the numbers in the range 0 - 10.

2) Write code that will print out all the numbers in the range 10 - 4000.

3) Write code that will print out every other number in the range 10 - 4000.

## Let's get even
1) Print out the even numbers that are within the range of 1 - 100.

2) Adjust your code to add a message next to the even number that says: "is an even number".

>Example Output:
```
2 is an even number
4 is an even number
6 is an even number
```

## Give me Five
1) For the numbers 0 - 100, print out "I found a `number`. High five!" if the number is a multiple of five.

>Example Output:
```
I found a 5. High five!
I found a 10. High five!
```

2) Add to the code from above to print out "I found a `number`. Three is a crowd" if the number is a multiple of three.

>Example Output:
```
I found a 3. Three is a crowd
I found a 5. High five!
I found a 6. Three is a crowd
I found a 9. Three is a crowd
I found a 10. High five!
```

## Savings account
1) Write code that will save the sum of all the numbers between 1 - 10 to a variable called `bank_account`.

>Check your work! Your banck_account should have $55 in it.

2) You got a bonus! Your pay is now doubled each week. Write code that will save the sum of all the numbers between 1 - 100 multiplied by 2.

>Check your work! Your banck_account should have $10,100 in it.


## Multiples of 3 and 5

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

:clap: You just solved [Project Euler](https://projecteuler.net/problem=1) problem 1! :clap:



### Easy Does It
1. Create an array that contains three quotes and store it in a variable called `quotes`.

### Random
Given the following array `const randomThings = [1, 10, "Hello", true]`

1. how do you access the 1st element in the array?

2. Change the value of `"Hello"` to `"World"`.

3. Check the value of the array to make sure it updated the array.

### We've Got Class
Given the following array `const ourClass = ["Gizmo", "Zoom", "Github", "Slack"]`

1. What would you write to access the 3rd element of the array?

2. Change the value of "Github" to "Octocat"

3. Add a new element, "Cloud City" to the array.

### Mix It Up
4. Given the following array `const myArray = [5 ,10 ,500, 20]`

1. using the `push` method, add the string `"Egon"` to the end of the array.

2. using a method, remove the string from the end of the array.

3. using the `unshift` method, add the string `"Bob Marley"` to the beginning of the array

4. using a different method, remove the string from the beginning of the array

5. use the reverse method on this array

### Biggie Smalls
Write an `if..else` statement:

1. console.log `little number` if the number is entered is less than **100**

2. If the number entered is 100 or more, alert `big number`.

### Monkey in the Middle
Write an `if...else if...else` statement:

1. console.log `little number` if the number entered is less than **5**.<br>

2.  If the number entered is more than 10, log `big number`.

3. Otherwise, console.log "monkey". <br>

### What's in Your Closet?

Below, we've given you examples of Kristyn and Thom's closets modeled as data in JavaScript.

```javascript
const kristynsCloset = [
  "left shoe",
  "cowboy boots",
  "right sock",
  "GA hoodie",
  "green pants",
  "yellow knit hat",
  "marshmallow peeps"
];

// Thom's closet is more complicated. Check out this nested data structure!!
const thomsCloset = [
  [
    // These are Thom's shirts
    "grey button-up",
    "dark grey button-up",
    "light blue button-up",
    "blue button-up",
  ],[
    // These are Thom's pants
    "grey jeans",
    "jeans",
    "PJs"
  ],[
    // Thom's accessories
    "wool mittens",
    "wool scarf",
    "raybans"
  ]
];
```

1. What's Kristyn wearing today? Using bracket notation to access items in `kristynsCloset`, log the sentence "Kristyn is rocking that " + *the third item in Kristyn's closet* + " today!" to the console.

2. Kristyn can't find her left shoe. Remove this item from her closet and save it to a variable named `kristynShoe`.

3. Kristyn just bought some sweet shades! Add `"raybans"` to her closet **after `"yellow knit hat"`.**

4. Kristyn spilled coffee on her hat... modify this item to read `"stained knit hat"` instead of yellow.

5. Put together an outfit for Thom! Using **bracket notation**, access the first element in Thom's `shirts` array.

6. In the same way, access one item from Thom's pants array.

7. Access one item from Thom's accessories array.

8. Log a sentence about what Thom's wearing. Example: `"Thom is looking fierce in a grey button-up, jeans and wool scarf!"`

9. Get more specific about what kind of PJs Thom's wearing this winter. Modify the name of his PJ pants to `Footie Pajamas`.


## Functions


### printGreeting

Write a function called `printGreeting` with a parameter `name` that returns a greeting with the argument **interpolated** into the greeting.

```javascript
console.log(printGreeting("Slimer"));
```

> => Hello there, Slimer!

<br>
<hr>

### reverseWordOrder

Write a function `reverseWordOrder` that accepts a single argument, a string. The function should return a string with the order of the words reversed. Don't worry about punctuation.

```javascript
console.log(reverseWordOrder("Ishmael me Call"));
```

> => "Call me Ishmael"


```
console.log(reverseWordOrder("I use Lâncome on my comb"));
```

> => "comb my on Lâncome use I"


<br>
<hr>

### calculate

Write a function called `calculate`.

This function should take three arguments, two numbers and a string.

Name the parameters `num1`, `num2`, and `operation`.

If the function receives the string "add" for the operation parameter, it will return the sum of num1 and num2.

If the function receives the string "sub" for the operation parameter, it will return num1 minus num2.

Do the same thing for multiplication "mult", division "div", and exponent "exp" (where num2 is the exponent of num1).

```javascript
console.log(calculate(4, 3, "sub"));

=> 1
```

```javascript
console.log(calculate(4, 3, "exp"));

=> 64
```

<br>
<hr>


# 1 

Write a function `printCool` that accepts one parameter, `name` as an argument. The function should print the name and a message saying that that person is cool.

```javascript
console.log(printCool("Captain Reynolds"));
```

> => "Captain Reynolds is cool";

# 2

Write a function `calculateCube` that takes a single number and prints the volume of a cube made from that number.

```javascript
console.log(calculateCube(5));
```

> => 125


# 3

Write a function `isAVowel` that takes a character (i.e. a string of length 1) and returns true if it is a vowel, false otherwise. The vowel could be upper or lower case.

```javascript
console.log(isAVowel("a"));
```

> => true


# 4

Write a function `getTwoLengths` that accepts two parameters (strings). The function should return an _array_ of numbers where each number is the length of the corresponding string.

```javascript
console.log(getTwoLengths("Hank", "Hippopopalous"));
```

> => [4, 13]


# 5 

Write a function `getMultipleLengths` that accepts a single parameter as an argument: an **array** of **strings**. The function should return an array of **numbers** where each number is the length of the corresponding string.


```javascript
console.log(getMultipleLengths(["hello", "what", "is", "up", "dude"]));
```

> => [5, 4, 2, 2, 4]


# 6

Define a function `maxOfThree` that takes three numbers as arguments and returns the largest of them. If all numbers are the same, it doesn't matter which one is returned. If the two largest numbers are the same, one of them should be returned.

```javascript
console.log(maxOfThree(6, 9, 1));
```

> => 9


# 7

Write a function `printLongestWord` that accepts a single argument, an **array** of **strings**. The method should return the longest word in the array. In case of a tie, the method should return the word that appears first in the array.

```javascript
console.log(printLongestWord(["BoJack", "Princess", "Diane", "a", "Max", "Peanutbutter", "big", "Todd"]));
```

> => "Peanutbutter"


# 8

Write a Javascript function called `transmogrify`. This function should accept three arguments, which you can assume will be numbers. Your function should return the "transmogrified" result.

The transmogrified result of three numbers is the product of the first two numbers, raised to the power of the third number.

For example, the transmogrified result of 5, 3, and 2 is `(5 times 3) to the
power of 2` is 225.

```javascript
console.log(transmogrify(5, 3, 2));
```

> => 225



### Objects

## Syntax

List and describe each individual piece of syntax that we use to construct an object. Don't leave anything out! The list is finite.

Example:

```
{} curly braces define the object.
```

<br>
<hr>

## Me

1. Create an empty object called `me`.<br>
2. Assign it properties for **name**, **age**, and **email** with corresponding values.<br>

The object would look something like this if we console logged it:

```javascript
console.log(me);
```

> => {name: "Kristyn", age: 98, email: "kristyn@foo.bar"}


3. Using dot notation, access the **name** property in your object.<br>
4. Without writing directly into the object, update the value of **age** to be 1000 years old.<br>
5. Using dot notation, verify that **age** has been updated.<br>
6. Add a key to this object called: "place of residence" and give it a value of your hometown. Note that the key has spaces, therefore you cannot use dot notation.
6. Access the value of "place of residence"<br>

<br>
<hr>

## Slimer

```javascript
const monster = {
   name: "Slimer",
   color: "greenish",
   type: "plasm or ghost or something"
}
```

* Given the **slimer** object:
    - What would you write to access the `name` and console.log it?
    - What would you write to change the `type` to 'creature' (without changing it inside the object)
    - What would you write to add a key to the object called `age`, and set the age to 6?
    - console.log the object to make sure `type` is creature, and `age` is 6

<br>
<hr>

## Ogres

Let's say you want to make an adventure game where you are an adventurer and you are going to fight **ogres**.

Using **objects**, create **models** and have them interact.

* how would you model your `adventurer`? Your adventurer will want a **name** and **hitpoints**. What else would your adventurer need?
* how would you model an `ogre`? Your ogre will want **hitpoints**.

* Write a very small program that will simulate a battle between your adventurer and an ogre. 
	* When your adventurer's hitpoints reach 0 the game is over.
	* When your ogre's hitpoints reach 0 the game is over.

* If you want to provide input to the game, you can run it in the Chrome console (but that isn't strictly necessary for now).

<br>
<hr>

# EXTRA STUFF

## Cat Combinator

### 1. Mama cat
* Define an object called `cat1` that contains the following properties:
	* name
	* breed
	* age (a number)

* console.log the cat's age
* console.log the cat's breed


### 2. Papa cat
* Define an object called `cat2` that also contains the properties:
	* name
	* breed
	* age (a number)


### 3. Combine Cats!

The cats are multiplying!

Write a function `combineCats` that has two parameters `mama`, and `papa`. The function will take two arguments -- each a cat object.

* Pass `cat1` and `cat2` as arguments to the `combineCats` function. The function should console.log them.

Example:

```javascript
combineCats(cat1, cat2)
```

> { name: "Joe", age: 19, breed: "Mog" }

> { name: "Jam", age: 45, breed: "Siamese" }


**This is to demonstrate that functions can take objects as arguments**

You could also invoke the `combineCats` function by writing the objects straight into the parentheses:

```javascript
combineCats({ name: "Craig", age: 20, breed: "unknown" }, { name: "Linda", age: 20, breed: "undefined" });
```
<br>

* Make it so the `combineCats` function will return a combination of the two incoming cats
	* The result should be an object wherein the
		* name is a concatenation of the parents' names
		* the age is 1
		* the breed is each of the parents' breeds with a hyphen in between

Example:

```javascript
console.log(combineCats(cat1, cat2));
```

Result:

![](https://i.imgur.com/CEB2ire.png)

**This is to demonstrate that a function can return an object**

<br>
<hr>

## 4. Cat brain bender

If `catCombinator` returns an **object**, and if `catCombinator` takes **objects** as **arguments**, then it stands to reason that:

`catCombinator` can use **itself** as its own argument.

Take a second to stew on that . . .

What is the result of:

```javascript
console.log(combineCats(combineCats(cat1, cat2), combineCats(cat1, cat2)));
```

Whoa . . .

The above console.log is **two levels** deep of combineCats.

* Write a console.log that is **three levels** deep of combineCats. combineCats should have two arguments, each which are combineCats, each which have two arguments, each which are combineCats.

Your output should look something like:

![](https://i.imgur.com/zuTzm5X.png)

<br>
<hr>


























