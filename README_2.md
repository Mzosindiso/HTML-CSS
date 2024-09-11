# JavaScript
We place JavaScript at the bottom of the page because, the browser reads the code in the order it appears in the file. <br>
If the script loads 1<sup>st</sup> and it is supposed to affect the HTML that has not loaded yet, there could be some issues. Placing JavaScript near the bottom of an HTML page is one way to accommodate this dependency.<br>
<strong>Variable</strong> - container that holds the data values, (stores/update/manipulate information).<br>
Javascript is <i><strong>case sensitive</i></strong>, <em>myVariable</em> is not the same as <em>myvariable</em>. You can’t use JavaScript keywords as variable names.<br>
To declare a variable: we use <b>let, const</b>.<br>
<code>let myVariable; //variable is now declared, we use <em>let</em> to declare viariable.
myVariable = "You"; //variable now has a value.
const age = 9; //is used for constants</code>

                            Data Types
1. String -sequence of characters used to represent text enclosed with single/double quote marks <code>let myVariable = 'You'; let myVariable = "You";</code><br>
2. Number -for numeric values, no quotes around them (let myVariable = 10;)
3. Boolean -for conditions/logical operations, special keywords that do not need quote marks <i><b>(True/False)</i></b> (let myVariable = True; / let myVariable = False;).
4. Array -allows you to store multiple values into a single reference/variable (let myVariable = [31, 12, 23];)
5. Object -can be anything, everything in Javascript is an object. Even the above examples fall under objects (let myVariable = document.querySelector('h1');).<br>

                           Types of Operators
Operators -are mathematical symbols/keywords that produces results based on two variables/values.
1. Arithmetic operators -addition(6+9), multiplication(6*9), subtraction(6-9), division(6/9), modulus(6%9) and exponential(6**).
2. Assignment operators -to assign values(=), (let myVariable = 90;).
3. Comparison operators -test values if they are equal and of the same data type, return a boolean result(true/false). equal(==), strictly equal(===), not equal(!=), not strictly equal(!==), greater than or equal to(>=), less than or equal to(<=), greater than(>) and less than(<).
4. Logical operators -used to combine multiple conditions, AND(&&), OR(||) and NOT(!).

Expressions -combination of values/variables into a single value.<br>
Functions -is a code snippet that can be called by other code, or itself even a variable that refers to a function.<br>
<code>//This function takes parameters
const power = function(base, exponent){
    let results = 1
    for(let count = 0; count < exponent; count++){
        results *= base
    }
    return results
}
console.log(power(3, 2))

//This function does not take parameters
const makeNoise = function(){
    console.log("Ping")
}
makeNoise()</code><br>
Scope -determines accessibility of functions and variables in different parts of code.<br>
<ul>
  <li>Global scope -variables declared outside of any function, can be accessed from anywhere in the code</li>
  <li>Local scope -variables declared within the function, cannot be accessed outside the local function</li>
  <li>Function scope -variables declared within the function, only accessed within the function</li>
  <li>Block scope -variables declared with <i>let</i> or <i>const</i> within the block({}) are only accessible within that block</li>
</ul><br>

                          Methods for selecting elements
<ul>
  <li>getElementById</li>
  <li>getElementByClassName</li>
  <li>getElementByTagName</li>
  <li>querySelector</li>
  <li>querySelectorAll</li>
</ul>

                          Statements
If-else statement <code>let passMark = 50; // passing mark
let failMark = 49; // failing mark

// Function to check someone is passing or failing
const checkResult = function(scoredMark) {
    if (scoredMark >= passMark) {
        console.log("Passed");
    } else {
        console.log("Failed");
    }
}
// Calling the function with a score of 70
checkResult(10);
</code>
