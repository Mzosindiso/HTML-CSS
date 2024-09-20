# JavaScript
<h4>Why learn JavaScript</h4>
<ol>
  <li>Popularity - one of the most used languages</li>
  <li>Versatility - used for many different things, webpages, APIs, mobile apps</li>
  <li>Easy to learn - compared to other loweer languages</li>
  <li>Community - support, resources and tools</li>
</ol>
<ul>
  <li>We place JavaScript at the bottom of the page because, the browser reads the code in the order it appears in the file.</li>
  <li>If the script loads 1<sup>st</sup> and it is supposed to affect the HTML that has not loaded yet, there could be some issues. Placing JavaScript near the bottom of       an HTML page is one way to accommodate this dependency.</li>
  <li><strong>Variable</strong> - container that holds the data values, (stores/update/manipulate information).</li>
  <li>Javascript is case sensitive, <em>myVariable</em> is not the same as <em>myvariable</em>. You can’t use JavaScript keywords as variable names.</li>
  <li>To declare a variable: we use <b>let, const</b>.<br>
  <code>let myVariable; //variable is now declared, we use <em>let</em> to declare viariable.
    myVariable = "You"; //variable now has a value.
  const age = 9; //is used for constants</code>
  </li>
  <li><b>Constant</b>: It’s a variable that’s read-only after its initial value is set.</li>
</ul>

<h4>Data Types</h4>
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
If-else statement: 
<code>
let passMark = 50; // passing mark
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

                          ES6+ & (Asynchronous programming)
1. <b>Template literals:</b> are delimited with backtick (<code>`</code>) characters, allowing for multi-line strings, string interpolation with embedded expressions.<br>
2. <b>Arrow functions:</b> they don't have their own bindings and should not be used as methods: <code>() => expression</code>.<br>
3. <b>Destructuring objects:</b> javascript expression that makes it possible to unpack values from arrays, or properties from objects, into distinct variables.<br>
4. <b>The spread operator</b> (<code>...</code>) syntax allows an iterable, such as an array or string, to be expanded in places where zero or more arguments (for function calls) or elements expected.<br>
5. <b>Asynchronous</b>, process that allows an application to run a second set of instructions while focusing on its primary or basic process.
6. <b>Promise</b> is an object that holds a future value of an async operation. It is able to notify anyone who is interested when its value is available<br>
7. <b>Callback</b> is a function passed into another function as an argument, which is invoked inside the outer funtion to complete some action.
8. 1. <code><i>async</i></code>, produces a promise when it is called, which is resolved when it returns and rejected when it throws an exception
   2. <code><i>await</i></code>, used inside an <i>async</i> function to pause execution until the promise is resolved or rejected, making the code appear linear.
9. <b>Error-handling</b>
<code>
try {
  // Try to execute this code.
}catch (exception) {
  // If there is an exception, run this code.
}finally {
  // This always gets executed regardless of whether an error was thrown or not.
}
</code>

<ul>
  <li>HTTP module is essential for creating web servers and handling HTTP requests and responses. It allows you to build the backbone of web applications and APIs.</li>
  <li>The FS module allows you to interact with the file system, enabling you to read, write, delete, and manipulate files within your Node.js applications.</li>
</ul>
