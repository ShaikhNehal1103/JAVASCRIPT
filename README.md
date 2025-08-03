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
        <center>
<hr>
    // 1. Full Name
    let firstName = "Ali";
    let lastName = "Khan";
    let fullName = firstName + " " + lastName;
    alert("Full name is: " + fullName);
<hr>
    // 2. "5" + 2
    let a = "5";
    let b = 2;
    let result1 = a + b;
    console.log("Result of '5' + 2 is: " + result1); // "52"
<hr>
    // 3. Complex increment/decrement
    let a1 = 10;
    let b1 = 5;
    let c = ++a1 + b1-- + --b1;
    console.log("Result of ++a + b-- + --b: " + c); // 19
<hr>
    // 4. Convert '20' to number and multiply by 3
    let str = "20";
    let num = Number(str);
    let result2 = num * 3;
    console.log("'20' * 3 = " + result2); // 60
<HR>
    // 5. Remainder 1 when divided by 3
    let remainder = 10 % 3;
    console.log("10 % 3 = " + remainder); // 1
<hr>
    // 6. Message with variables
    let student = "Hassan";
    let score = 88;
    alert(student + " got " + score + " marks in JavaScript!");
<hr>
    // 7. Combined pre/post increment
    let x = 5;
    let y = x++ + ++x - --x;
    console.log("x++ + ++x - --x = " + y); // 6
<hr>
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
<hr>
    // 9. Perfume bill
    let perfumePrice = 2500;
    let totalBill = perfumePrice * 4;
    alert("Total bill for 4 perfumes: " + totalBill + " PKR");
<hr>
    // 10. Custom math expression
    let marks = 85;
    let finalResult = marks + 5 * 2 - 10;
    // 5*2=10 → 85+10=95 → 95-10 = 85
    console.log("Custom expression result: " + finalResult);

    // Bonus:
    let msg = "Total: " + (5 + 5) * 2;
    alert(msg); // Output: "Total: 20"
  </script>
  </center>
  <hr>

</body>
</html>
