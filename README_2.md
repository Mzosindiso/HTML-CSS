# JavaScript
We place JavaScript at the bottom of the page because, the browser reads the code in the order it appears in the file. <br>
If the script loads 1<sup>st</sup> and it is supposed to affect the HTML that has not loaded yet, there could be some issues. Placing JavaScript near the bottom of an HTML page is one way to accommodate this dependency.<br>
<strong>Variable</strong> - container that holds the data values, (stores/update/manipulate information).<br>
Javascript is <i><strong>case sensitive</i></strong>, <em>myVariable</em> is not the same as <em>myvariable</em>. <br>
To declare a variable: we use <b>let, const</b>.
let myVariable; (variable is now declared, we use <em>let</em> to declare viariable).<br>
const age = 9; (is used for constants)
myVariable = "You"; (variable now has a value).<br>

                            Data Types
1. String -sequence of characters used to represent text enclosed with single/double quote marks (let myVariable = 'You'; / let myVariable = "You";).<br>
2. Number -for numeric values, no quotes around them (let myVariable = 10;)
3. Boolean -for conditions/logical operations, special keywords that do not need quote marks <i><b>(True/False)</i></b> (let myVariable = True; / let myVariable = False;).
4. Array -allows you to store multiple values into a single reference/variable (let myVariable = [31, 12, 23];)
5. Object -can be anything, everything in Javascript is an object. Even the above examples fall under objects (let myVariable = document.querySelector('h1');).

                            Types of Operators
Operators -are mathematical symbols/keywords that produces results based on two variables/values.
1. Arithmetic operators -addition(6+9), multiplication(6*9), subtraction(6-9), division(6/9), modulus(6%9) and exponential(6**).
2. Assignment operators -to assign values(=), (let myVariable = 90;).
3. Comparison operators -test values if they are equal and of the same data type, return a boolean result(true/false). equal(==), strictly equal(===), not equal(!=), not strictly equal(!==), greater than or equal to(>=), less than or equal to(<=), greater than(>) and less than(<).
4. Logical operators -used to combine multiple conditions, AND(&&), OR(||) and NOT(!).

Expressions -combination of values/variables into a single value.



