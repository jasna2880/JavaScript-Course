# Lesson 7 – Functions (JavaScript)

## Instructions
Create separate HTML files for each exercise  
(example: `7a.html`, `7b.html`, `7c.html`, etc.)

---

## Exercises

### 7a. Basic Function
- Create a function called `greet`
- The function should display **"Hello!"** in the Console
- Call the function multiple times

---

### 7b. Function With Parameter
- Add a parameter called `name` to the `greet` function
- Display the message:  
  **"Hello ${name}!"**
- Call the function with different names  
  Example: `greet('Simon')`

---

### 7c. Handle Undefined Name
- Call `greet()` without passing a name
- Update the function so that:
  - If `name` is **undefined**
  - Display **"Hi there!"** instead

Hint:
if (!name) { ... }


---

### 7d. Celsius to Fahrenheit
- Create a function `convertToFahrenheit(celsius)`
- It should return the temperature in Fahrenheit

Formula:
Fahrenheit = (Celsius × 9 / 5) + 32


Example:
convertToFahrenheit(25) → 77


---

### 7e. Fahrenheit to Celsius
- Create a function `convertToCelsius(fahrenheit)`
- It should return the temperature in Celsius

Formula:
Celsius = (Fahrenheit − 32) × 5 / 9


Example:
convertToCelsius(86) → 30


---

### 7f. Convert Temperature
- Create a function `convertTemperature(degrees, unit)`
- `unit` will be `'C'` or `'F'`
- Convert to the other unit
- Return the result as a **string**
- Reuse functions from 7d and 7e

Examples:
convertTemperature(25, 'C') → '77F'
convertTemperature(86, 'F') → '30C'


---

### 7g. Convert Length (km ↔ miles)
- Create a function `convertLength(length, from, to)`
- Supported units: `km`, `miles`
- 1 mile ≈ 1.6 km

Examples:
convertLength(50, 'miles', 'km') → '80 km'
convertLength(32, 'km', 'miles') → '20 miles'
convertLength(50, 'km', 'km') → '50 km'


---

### 7h. Add Feet Support
- Update `convertLength` to support:
  - `km`
  - `miles`
  - `ft`

Conversions:
- 1 mile = 5280 ft
- 1 km = 3281 ft (approx)

Examples:
convertLength(5, 'miles', 'ft') → '26400 ft'
convertLength(5, 'km', 'ft') → '16405 ft'


---

### 7i. Invalid Unit Handling
- If user enters an invalid unit
- Return the message:
Invalid unit: ${unit}


Example:
convertLength(5, 'lbs', 'lbs') → 'Invalid unit: lbs'


---

## Challenge Exercises

### 7j. Calculator Refactor
- Copy the Calculator project from Lesson 5
- Notice repeated code in button logic
- Create a function `updateCalculation()`
- Reuse it to make the code cleaner

---

### 7k. Cart Quantity Refactor
- Copy the Cart Quantity project from Lesson 6
- Create a function `updateCartQuantity()`
- Use it for all buttons

---

### 7l. Early Return
- Modify `updateCartQuantity()`
- If quantity is invalid:
  - Show an alert
  - Use `return;` immediately
- This removes unnecessary `else if` blocks
- Makes code cleaner and easier to read

---

## Concepts Covered
- Functions
- Parameters
- Return values
- Reusing functions
- Conditional logic inside functions
- Early return