<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!DOCTYPE html>
<html>
<head>
  <title>JavaScript Practice</title>
</head>
<body>

  <h2>JavaScript Practice Output</h2>
  <p>Open the console to see results.</p>

  <script>
    // 1. Full Name
    let firstName = "Ali";
    let lastName = "Khan";
    let fullName = firstName + " " + lastName;
    alert("Full name is: " + fullName);

    // 2. "5" + 2
    let a = "5";
    let b = 2;
    let result1 = a + b;
    console.log("Result of '5' + 2 is: " + result1); // "52"

    // 3. Complex increment/decrement
    let a1 = 10;
    let b1 = 5;
    let c = ++a1 + b1-- + --b1;
    console.log("Result of ++a + b-- + --b: " + c); // 19

    // 4. Convert '20' to number and multiply by 3
    let str = "20";
    let num = Number(str);
    let result2 = num * 3;
    console.log("'20' * 3 = " + result2); // 60

    // 5. Remainder 1 when divided by 3
    let remainder = 10 % 3;
    console.log("10 % 3 = " + remainder); // 1

    // 6. Message with variables
    let student = "Hassan";
    let score = 88;
    alert(student + " got " + score + " marks in JavaScript!");

    // 7. Combined pre/post increment
    let x = 5;
    let y = x++ + ++x - --x;
    console.log("x++ + ++x - --x = " + y); // 6

    // 8. Illegal vs legal variable names (shown as comments)
    // let var = 5;  Reserved keyword
    // let 123abc = "test";  Starts with number
    // let user-name = "Ali";  Hyphen not allowed
    // let let = "value";  Reserved word
    // let full name = "Ali Khan";  Space not allowed

    //  Corrected:
    let myVar = 5;
    let abc123 = "test";
    let userName = "Ali";
    let letValue = "value";
    let fullNameCorrect = "Ali Khan";

    // 9. Perfume bill
    let perfumePrice = 2500;
    let totalBill = perfumePrice * 4;
    alert("Total bill for 4 perfumes: " + totalBill + " PKR");

    // 10. Custom math expression
    let marks = 85;
    let finalResult = marks + 5 * 2 - 10;
    // 5*2=10 → 85+10=95 → 95-10 = 85
    console.log("Custom expression result: " + finalResult);

    // Bonus:
    let msg = "Total: " + (5 + 5) * 2;
    alert(msg); // Output: "Total: 20"
  </script>
  <hr>
<p>1. Create a full name message using variables. Combine first and last name into fullName and alert it.
javascript
Copy
Edit
let firstName = "Ali";
let lastName = "Khan";
let fullName = firstName + " " + lastName;
alert("Full name is: " + fullName);
<hr>
2. What will be the output of:
javascript
Copy
Edit
let a = "5";
let b = 2;
let result = a + b;
console.log(result);
 Output:
arduino
Copy
Edit
"52"
 Why:
Because a is a string ("5") and b is a number (2).
The + operator in JavaScript acts as string concatenation if any operand is a string.
So it combines "5" and 2 as "52".
<hr>

3. Guess the output and explain:
javascript
Copy
Edit
let a = 10;
let b = 5;
let c = ++a + b-- + --b;
console.log(c);
 Output:
Copy
Edit
27
❓ Explanation:
++a → pre-increment → a becomes 11

b-- → post-decrement → uses 5, then b becomes 4

--b → pre-decrement → b becomes 3

So:

ini
Copy
Edit
c = 11 + 5 + 3 = 19
But wait... that’s wrong, sorry — let's recalculate properly.

Actually:

++a = 11

b-- = 5 (then b = 4)

--b = 3 (decremented again)

So:

ini
Copy
Edit
c = 11 + 5 + 3 = 19
 Final Answer: 19
<hr>

4. Convert string '20' to a number and multiply it with 3. Show the output.
javascript
Copy
Edit
let str = "20";
let num = Number(str); // or parseInt(str)
let result = num * 3;
console.log(result); // 60
Output:

Copy
Edit
60
<hr>
5. Write an expression that gives the remainder 1 when divided by 3.
<br>
let result = 10 % 3;
7 % 3 = 1
<HR>
6. Using the variables below, alert the message:
JavaScript
<br>
Copy
Edit
let student = "Hassan";
let score = 88;
alert(student + " got " + score + " marks in JavaScript!");
 Output:</p>
</body>
</html>
