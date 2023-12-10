# დავალება 1

```
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <style>
      #container {
        width: 200px;
        height: 200px;
        background: green;
        position: relative;
      }
      #box {
        width: 50px;
        height: 50px;
        background: red;
        position: absolute;
      }
      </style>
      <div id="container">
         <div id="box"> </div>
      </div>
      <script>
        var pos = 0; 
        //our box element
        var box = document.getElementById("box");
        var t = setInterval(move, 10);

        function move() {
          if(pos >= 150) {
            clearInterval(t);
          }
          else {
            pos += 1;
            box.style.left = pos+"px";
          }
        }
      </script>
  </body>
</html>
```
ამ კოდში როცა წითელი ყუთი  მწვანე ყუთის მარჯვენა მხარეს მივა, უკან რო დაბრუნდეს მარცხენა მხარეს, და მარცხენა მხარეს რომ მივა ისევ მარჯვენა მხარეს რომ მივიდეს და ეს ციკლი სამუდამოდ გაგრძელდეს
და Sololearn Creating Animation-ის ჩათვლით

# დავალება 2

1) გააკეთე წიგნის ობიექტი რომელსაც ექნება ეს ფროფერთიები: title, author,  years . და ამ ფროფერთიებში მომხმარებელმა უნდა შეიტანოს prompt ის საშუალებეით თითოეული ფროფერთის მნიშვნელობა
2) მეორე. გააკეთონ ობიექტი რომელსაც ერქმევა Circle და ექნება ფროფერთი Radius და მეთოდი calculateArea. როცა მომხმარებელი შემოიტანს რადიუსს ამ ობიექტში calculateArea მეთოდი გამოითვლის ამ წრის ფართობს.
3) შექმენით ობიექტი რომელსაც ერქმევა Student, მისი ფროფერთიები იქნება firstName, lastName და მასივი რომელსაც ერქმევა grades, მომხმარებელმა უნდა შემოიტანოს ეს ყველა ინფორმაცია(grades რამოდენიმე უნდა იყოს) გადააქციონ მომხმარებლის ნიშნები მასივად და მიანიჭონ ის grades ცვლადს, აგრეთვე შექმენით მეთოდი რომელიც გამოითვლის Average Scores ს Student ობიექტში

# დავალება 3

Event Handling დავალებები
1) Button Click Counter

 
Create a webpage with a button and a counter.
Write JavaScript to increment the counter each time the button is clicked.
Display the updated count on the webpage.
 
2) Mouse Hover Color Change

 
Create a webpage with a div element.
Write JavaScript to change the background color of the div when the mouse hovers over it.
Change it back to the original color when the mouse leaves the div.
 
3) Show/Hide Content:

Create a button and a paragraph of text on a webpage.
Write JavaScript code to toggle the visibility of the paragraph when the button is clicked.
If it's visible, hide it; if it's hidden, show it.
 
4) Change Background Color on Button Click:

Create a webpage with a button and a blank area (e.g., a div) to serve as the content area.
Write JavaScript code to change the background color of the content area when the button is clicked.
Define a few different background colors, and each time the button is clicked, cycle through these colors.

# დავალება 4

Exercise 1: Event Bubbling
Create a nested set of HTML elements (e.g., divs inside divs). Add event listeners to both the inner and outer elements to demonstrate event bubbling. Log a message indicating which element's event handler was triggered.
Exercise 2: Event Capturing
Modify Exercise 2 to demonstrate event capturing. Add event listeners with the true parameter to listen for events during the capturing phase. Again, log a message indicating which element's event handler was triggered.

# დავალება 5

მოიფიქრეთ რაიმე საიტის იდეა, და გააკეთეთ მაგ საიტის ნავიგაცია, Hero სექცია, და ასევე ეს საიტი უნდა იყოს რესპონსივი

# დავალება 6

Task 1: String.fromCharCode()

Write a function called unicodeToString that takes an array of Unicode values and returns the corresponding string.

Use the String.fromCharCode() method to convert each Unicode value to its corresponding character.

Test your function with a sample array of Unicode values and log the resulting string to the console.

Task 2: charCodeAt()

Write a function called stringToUnicode that takes a string as input and returns an array of Unicode values representing each character.

Use the charCodeAt() method to obtain the Unicode value for each character.

Test your function with a sample string and log the resulting array of Unicode values to the console.

# დავალება 7

Task 1: Sorting Numbers

Write a function called sortNumbers that takes an array of numbers as input and returns a new array of numbers sorted in ascending order.

Test your function with a sample array of numbers and log the sorted result to the console.

Task 2: Filtering Numbers

Using the same array of numbers from Task 1, write a function called filterEvenNumbers that takes one argument: an array of numbers.

The function should return a new array containing only the even numbers.

Test your function with a sample array of numbers and log the filtered result to the console.

# დავალება 8

Exercise 1: Variable Scopes
Create a JavaScript program that demonstrates variable scopes. Declare a global variable and a local variable with the same name. Inside a function, try to access both variables and log their values. Explain the results.
Exercise 2: Selecting Elements by ID
Create an HTML document with several elements, each with a unique ID. Write a JavaScript function that uses document.getElementById() to select and manipulate one of these elements. For example, you could change its text or style.

Exercise 3: Selecting Elements by Class
Create an HTML document with multiple elements that have the same class name. Write a JavaScript function that uses document.getElementsByClassName() to select all elements with that class and change their text or style.
Exercise 4: Selecting Elements by Tag Name
Create an HTML document with various elements of the same type (e.g., <p> or <div>). Write a JavaScript function that uses document.getElementsByTagName() to select all elements of that type and modify their content or attributes.

# დავალება 9

Create an Object: Declare an empty object named person.

Add Properties: Add properties name, age, and email to the person object with values of your choice.

Access Property: Access and log the name property of the person object.

Modify Property: Change the age property of the person object to a new value.

Add Method: Add a method called introduce to the person object that logs a greeting message with the person's name and age.

Nested Objects: Create an object called address with properties street, city, and postalCode. Add this as a property of the person object.

Access Nested Property: Access and log the city property within the address object.

Object Comparison: Create two objects, person1 and person2, with the same properties and values. Check if they are equal.

Object Iteration: Create a function that loops through and logs all properties and their values of the person object.

Object Deletion: Remove the email property from the person object.

Object Length: Write a function that counts and logs the number of properties in the person object.

Object Keys: Write a function that logs all the keys (property names) of the person object.

Object Values: Write a function that logs all the values of the properties in the person object.
Function Declaration: Declare a function named greet that logs "Hello, world!" when called.

Function Expression: Create a variable sayHi and assign it a function expression that logs "Hi there!" when called.

Function Parameters: Write a function called add that takes two parameters, a and b, and returns their sum.

Function Invocation: Call the add function from exercise 3 with arguments 7 and 3, and log the result.

Function Scope: Declare a variable x inside a function. Try to log the value of x outside of that function. What does it log?

Arrow Function Exercises:

Arrow Function Basics: Create an arrow function called double that takes a number as a parameter and returns its double.

Arrow Function with Implicit Return: Refactor the greet function from exercise 1 using an arrow function with an implicit return.

Arrow Function in Object: Create an object person with an arrow function property sayHello that logs "Hello!" when called.
default values in function

# დავალება 10

შექმენით Counter პროექტი

# დავალება 11

1) For Of Loop
2) For In Loop
3) ... Spread Operator
4) Default Functions
5) Object Add Methods
6) Project With Your Creativity

# დავალება 12

1) Object.assign()
2) Computed Keys in object
3) For Of Loop
4) For In Loop
5) ... Spread Operator
6) Default Functions
7) Object Add Methods
8) Project With Your Creativity

# დავალება 13

1) გააკეთეთ 2-2 მაგალითები 1. For Each 2. Map 3. Filter 4. Reduce

2) დაშალეთ სამ ელემენტიანი მასივი სამ ცვლადად. 
დაშალეთ სამ ელემენტიანი ობიექტი და ყველა კუთვნილებას მიანიჭე ახალი სახელი

3) დაშალეთ სამ ელემენტიანი მასივი ისე რომ შუა ელემენტის გარდა თითოეულის მნიშვნელობა მიანიჭე ცვლადებს
და ასევე აქ იყოს Default მნიშვნელობები

4) რესტზე იყოს 2 მაგალითი

# დავალება 14

HW #1
Task: Create a class Rectangle with properties for width and height. The class should have methods to calculate area and perimeter. Instantiate a few rectangles and display their area and perimeter.
HW #2
Task: Extend the Rectangle class to create a Square class. The Square class only needs one side length (as opposed to width and height). Ensure that you can still calculate area and perimeter for the square.
HW #3
Task: Create a class Library and a class Book. The Library class should have a property that is an array of Book objects. Implement methods in the Library class to add books, remove books, and find books by title or author.
HW #4
Create a new JavaScript file named circle.js
Create a class named Circle
The class should have two properties:
Pi: This should be a static property with a value of 3.14159. (You can use the built-in Math.PI for a more accurate value if desired.)
radius: This should be a dynamic property initialized through the constructor.
The constructor of the Circle class should accept one parameter, radius.
Ensure that the radius is positive. If a negative radius or zero is provided, throw an error with a relevant message.
area(): This method should return the area of the circle. Formula: Pi * radius^2.
perimeter(): This method should return the perimeter (circumference) of the circle. Formula: 2 * Pi * radius.

# დავალება 15: 

HW #1
Create Classes: Design and implement the following JavaScript classes:

Natural: Represents a natural number.
Integer: Represents an integer number.
Rational: Represents a rational number (fraction).
Irrational: Represents an irrational number.
Real: Represents a real number.
Imaginary: Represents an imaginary number.
Complex: Represents a complex number.
Properties and Methods: Each class should have appropriate properties and methods related to its mathematical concept. Define constructors and any necessary methods for each class.

Demonstration: Create instances of these classes in your JavaScript program. Demonstrate the usage of these classes by performing operations or calculations relevant to each concept.

Documentation: Add comments to your code to explain the purpose of each class and its methods.

Bonus:
For an extra challenge, you can implement additional features such as:

Overloading operators (e.g., +, -, *) for mathematical operations between objects of different classes.
Implementing mathematical operations (e.g., addition, subtraction, multiplication) for the Complex class.
HW #2
Objective: To create a JavaScript class Languages that represents a database of programming languages. Each programming language should be represented as an object with attributes like name, creator, year, and a brief description.

Requirements:

Create a class called Languages that will serve as the programming languages database.

Implement a method within the Languages class to add a new programming language to the database. This method should take parameters for the name, creator, year, and description of the language and create a new language object. The method should then add this object to the database.

Implement a method to retrieve information about a specific programming language by name. This method should take the name of the language as a parameter and return the details (name, creator, year, description) of that language.

Implement a class method within the Languages class to list all the programming languages in the database, displaying their names in alphabetical order.

Create an instance of the Languages class and add at least five different programming languages to the database.

Demonstrate the use of your Languages class by adding, retrieving, and listing programming languages in a JavaScript program.

# დავალება 16

Time for some OOP fun!

Define a class Person with the following properties:

A constructor that accepts 4 arguments: firstName/FirstName (defaults to "John" if not set), lastName/LastName (defaults to "Doe" if not set), age/Age (defaults to 0 if not set) and gender/Gender (defaults to "Male" if not set). These should be stored in this.firstName/this.FirstName, this.lastName/this.LastName, this.age/this.Age and this.gender/this.Gender respectively.
A method sayFullName/SayFullName that accepts no arguments and returns the full name (e.g. "John Doe")
A class/static method greetExtraTerrestrials/GreetExtraTerrestrials that accepts one parameter raceName and returns "Welcome to Planet Earth raceName". For example, if the race name is "Martians", it should say "Welcome to Planet Earth Martians"
You may use any valid syntax you like; however, it is highly recommended that you complete this Kata using ES6 syntax and features.

Have fun! :D

Starting Code:
 ```
 class Person {
  // Get coding in ES6 :D
}
 ```

# დავალება 17

Map, Reduce, და Filter, გააკეთე ამათი კოპიო

# დავალება 18

HW #1
Tasks:

Map Usage:

Create a JavaScript Map that represents a dictionary of words and their corresponding meanings. Populate the Map with at least 5 word-meaning pairs. Then, write a function that allows the user to enter a word and displays its meaning if it exists in the dictionary. If the word is not found, display an appropriate message.

Set Operations:

Create two sets of integers, Set A and Set B, with a minimum of 5 elements each. Implement functions to perform the following set operations and display the results:

Union: Create a function that computes and displays the union of Set A and Set B.
Intersection: Create a function that computes and displays the intersection of Set A and Set B.
Difference: Create a function that computes and displays the difference between Set A and Set B (elements that are in Set A but not in Set B).
Unique Words:

Write a function that takes a string as input and returns a Set containing all unique words in the string. Ignore punctuation and consider words in a case-insensitive manner. Test the function with various input strings.

Frequency Counter:

Write a function that takes a string as input and returns a Map where keys are words in the string, and values are the frequency of each word's occurrence in the string. Ignore punctuation and consider words in a case-insensitive manner. Test the function with a sample text.
HW #2
Tasks:

Class Creation:

Create a JavaScript class named Person with the following properties:

firstName (string)
lastName (string)
age (number)
Setter Methods:

Implement setter methods for each of the properties (setFirstName, setLastName, and setAge) that allow you to update the values of these properties. The setter methods should perform validation:

The setFirstName and setLastName methods should only accept non-empty strings.
The setAge method should only accept positive numbers.
Getter Methods:

Implement getter methods for each property (getFirstName, getLastName, and getAge) to retrieve the values of these properties.

Usage Example:

Create an instance of the Person class and demonstrate the use of setter and getter methods by setting values and retrieving them. Also, demonstrate what happens when invalid values are provided to the setters.
HW #3
Class Creation:

Create a JavaScript class named BankAccount with the following properties:

_accountNumber (string)
_balance (number)
Both _accountNumber and _balance should be private properties and not directly accessible from outside the class.

Private Methods:

Implement the following private methods within the BankAccount class:

_generateAccountNumber(): A private method that generates a random 10-digit account number and sets it to the _accountNumber property. This method should be called when a BankAccount instance is created.

_isNegative(amount): A private method that takes an amount as a parameter and returns true if the amount is negative, otherwise false.

_isValidWithdrawal(amount): A private method that takes an amount as a parameter and returns true if the withdrawal amount is valid (not negative and does not exceed the current balance), otherwise false.

Public Methods:

Implement the following public methods within the BankAccount class:

getBalance(): A public method that returns the current balance.

deposit(amount): A public method that takes an amount as a parameter and deposits it into the account. If the amount is positive, update the balance; otherwise, display an error message.

withdraw(amount): A public method that takes an amount as a parameter and withdraws it from the account if it's a valid withdrawal amount. If the amount is negative or exceeds the balance, display an error message.

Usage Example:

Create an instance of the BankAccount class, demonstrate the use of public methods to deposit and withdraw money, and ensure that private properties and methods are properly encapsulated. 

# დავალება 19

Homework Assignment: Function Composition with bind:
Your task is to create a series of JavaScript functions that perform specific tasks. Then, use the bind method to compose these functions together into a pipeline. Imagine you are building a data processing pipeline, and each function represents a step in that pipeline. By the end of this assignment, you should have a clear understanding of how to use bind to create reusable function compositions.

Homework Assignment: Real-world Scenario with call and apply:
For this assignment, let's dive into a real-world scenario: simulating a restaurant ordering system. Your goal is to create JavaScript objects representing customers, menu items, and orders. Use the call and apply methods to model the process of customers placing orders. By the end, you'll gain practical experience in how these methods can be applied in real-life situations.

Homework Assignment: Performance Comparison:
In this assignment, we'll explore the performance of JavaScript methods. Your task is to perform a time-sensitive operation, like sorting a large array, using two different techniques. One approach should utilize native JavaScript methods, and the other should incorporate bind, call, or apply. Measure and compare the performance of these methods and provide an analysis of the results. This assignment will help you understand when and how to choose the most efficient method for a given task.

# დავალება 20

HW #1
შექმენით ახალი სოლოლერნის ექაუნთი და მთელი ჯავასკრიპტი გაიარეთ თავიდან

HW #2
ორი api რაც გავაკეთეთ (weather და country) და ამათ გაუკეთეთ დიზაინი
თუ გინდათ სხვა api აირჩიეთ და იმას გაუკეთეთ დიზაინი.~

# დავალება 21

შექმენით ქაუნთერის პროექტი (CSGO არა) რეაქთის გამოყენებით

# დავალება 22

შექმენით To Do List თეილვინდით და რეაქთით

# დავალება 23

ვანილა ჯავასკრიპტით და რეაქთით ორივეთი შექმენით Todo List
რეაქთთან ერთად გამოიყენეთ Tailwindcss
და მეორე შექმენით თავისუფალი პროექტი React + Tailwindcss