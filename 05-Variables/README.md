## Lesson 5 – Variables (JavaScript)

Instructions:
Create separate HTML files for each exercise (5a.html, 5b.html, etc.).

## Exercises:

5a. Create a <script> element. Inside it, create a variable called `name` and store your name as a string.

5b. Display the message `My name is: <name>` in the Console using the variable from 5a.

5c. At a restaurant, you order 1 coffee ($5), 2 bagels ($3 each), and 1 soup ($9).
Calculate the total cost and store it in a variable called `cost`.

5d. Display `Cost of food: $<cost>` in the Console.

5e. The restaurant charges a 10% tax.
Using the `cost` variable, calculate the tax (cost * 0.1) and store it in a variable.

5f. Display `Tax (10%): $<tax>` in the Console.

5g. Calculate the total cost (cost + tax), store it in `totalCost`,
and display `Total cost: $<totalCost>` in the Console.

5h. In the Cart Quantity project, add buttons `+4` and `+5`
to increase the cart quantity using the `+=` operator.

5i. Add a button `Remove from cart` that decreases the quantity by 1.

5j. Add buttons `-2` and `-3` that decrease the quantity by 2 and 3.

5k. Use the shortcut operators `--` and `-=` in exercises 5i and 5j.

## Challenge Exercises:

We will build a calculator step by step.

Setup:
Open https://supersimple.dev/projects/calculator
and observe how the calculator works using the Console.

Create a new file named `calculator.html`.

5l. Add the full HTML structure and set the page title to `Calculator`.

5m. Create the buttons: `1`, `2`, `3`, and `+`.

5n. Inside a <script>, create a variable:
`let calculation = "";`
This will store calculations like `1+2` or `11+2+2`.

5o. When clicking the `1` button, add `'1'` to `calculation`
and display it in the Console.

5p. Do the same for the `2`, `3`, and `+` buttons.

5q. When clicking the `=` button, use `eval(calculation)`
to calculate the result, store it back in `calculation`,
and display the result in the Console.

5r. Create the remaining calculator buttons.
Use <p> elements to arrange buttons into multiple rows.

## Concepts Used:
Variables, strings, numbers, arithmetic operations,
console.log(), +=, -=, --, eval(), button click handling
