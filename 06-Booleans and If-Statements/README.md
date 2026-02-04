# Lesson 6 – Booleans and If Statements (JavaScript)

## Instructions
Create separate HTML files for each exercise  
(example: `6a.html`, `6b.html`, `6c.html`, etc.)

---

## Exercises

### 6a. Hour-based Greeting
- Create a variable called `hour`
- Save the current hour (0–23, 24-hour format)
- Use if–else statements:
  - If hour is between **6 and 12** → display **"Good morning!"**
  - If hour is between **13 and 17** → display **"Good afternoon!"**
  - Otherwise → display **"Good night!"**
- Display the message in the Console

---

### 6b. Change Hour Value
- Change the value of `hour`
- Observe different messages in the Console

---

### 6c. Greeting With Name
- Create a variable called `name`
- Store your name as a string
- Update the greeting messages to include your name  
  Example: `Good morning ${name}!`

---

### 6d. Discount Eligibility
Imagine an amusement park discount:
- Children **6 years and under**
- Seniors **65 years and older**

Steps:
- Create a variable `age`
- Use an if-statement to check eligibility
- If eligible → display **"Discount"**
- Otherwise → display **"No discount"**
- Try using the `||` (OR) operator
- Change `age` to test different outputs

---

### 6e. Holiday Condition
- Create a variable: `isHoliday`
- Set it to `true` or `false`
- Discount should apply only if:
  - Person is eligible **AND**
  - It is **not** a holiday
- Use `&&` (AND) operator
- Use brackets `()` if needed
- Change `isHoliday` to test behavior

---

## Coin Flip Game

(Create a new HTML file for exercises 6f – 6j)

---

### 6f. Generate Random Number
- Use `Math.random()`
- Save the value in a variable

---

### 6g. Heads or Tails
- If number < 0.5 → display **"heads"**
- Else → display **"tails"**
- Show result in the Console

---

### 6h. Store Result
- Instead of directly logging,
- Save the result in a variable called `result`

---

### 6i. Guess the Result
- Create a variable `guess`
- Store either `"heads"` or `"tails"`
- If guess matches result → display **"You win!"**
- Otherwise → display **"You lose!"**

---

### 6j. (Challenge)
- Rewrite previous if-else logic
- Use **ternary operator**  
  `(condition ? value1 : value2)`

---

## Challenge Exercises – Cart Quantity Project

### Setup
- Make a copy of the Cart Quantity project from Lesson 5

---

### 6k. Maximum Quantity Check
- Maximum cart quantity = **10**
- Before updating quantity:
  - If quantity > 10:
    - Show popup **"The cart is full"**
    - Do NOT update quantity
  - Else:
    - Update quantity
    - `console.log()` the value

---

### 6l. Minimum Quantity Check
- Before decreasing quantity:
  - If quantity < 0:
    - Show popup **"Not enough items in the cart"**
    - Do NOT update quantity
  - Else:
    - Update quantity
    - `console.log()` the value

---

## Concepts Covered
- Booleans
- if / else if / else
- Logical operators (`&&`, `||`)
- Ternary operator
- Math.random()
- Console logging
- Basic game logic
