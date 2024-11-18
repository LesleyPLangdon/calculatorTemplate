# Calculator Project Instructions

## Instructions
You will create a basic calculator that performs addition, subtraction, multiplication, and division. This project will help you apply what you've learned about functions, DOM manipulation, and basic error handling in JavaScript.

---

## Plan

### Objective
Define the purpose of the calculator.

### Features
- **Input Handling**: Users input numbers and operations via buttons.
- **Operations**: The calculator performs the selected operation when the equal button (`=`) is clicked.
- **Clear Functionality**: A "Clear" button resets the calculator.

### Requirements
1. The calculator must perform four operations: addition, subtraction, multiplication, and division.
2. Users will interact with the calculator using buttons for numbers (`0-9`) and operations (`+`, `-`, `*`, `/`).
3. A display area will show the current input and the result.
4. Implement error handling to:
   - Prevent division by zero.
   - Handle invalid or incomplete operations.
5. This calculator only needs to process a single operation at a time.

---

### Break Down the Problem
1. **Variables**:
   - `currentInput`: Stores the user's current input.
   - `previousInput`: Stores the previous value.
   - `operation`: Stores the selected operation.
2. **Functions**:
   - Handle number button clicks.
   - Handle operation button clicks.
   - Perform the calculation.
   - Reset the calculator.

---

### Edge Cases
- Division by zero.
- Pressing `=` without valid inputs.
- Resetting the calculator when incomplete data is entered.

---

## Design

### HTML Structure
- A grid-based structure with buttons for:
  - Digits (`0-9`).
  - Operations (`+`, `-`, `*`, `/`).
  - Equal (`=`) and Clear buttons.
- A display area to show inputs and results.

---

### Visual Layout
Attach a wireframe showing the design.

---

## Function Design

### Write Pseudo Code for Each Function
1. **`add(num1, num2)`**: 
   - Accepts two numbers as parameters and adds them.

2. **`subtract(num1, num2)`**: 
   - Accepts two numbers as parameters and subtracts `num2` from `num1`.

3. **`multiply(num1, num2)`**: 
   - Accepts two numbers as parameters and multiplies them.

4. **`divide(num1, num2)`**: 
   - Accepts two numbers as parameters and divides `num1` by `num2`.

5. **`clear()`**:
   - Resets all variables and updates the display.

6. **`calculate()`**:
   - Takes user inputs and returns the correct answer.

---

## Implement
1. Write your code in JavaScript.
2. Include **descriptive comments** for readability.

---

## Test

### Unit Testing
Test each function individually:
- `add()`
- `subtract()`
- `multiply()`
- `divide()`
- `clear()`
- `calculate()`

### Edge Cases
1. Division by zero.
2. Non-numeric input.

### User Input Tests

| Calculation | First Number | Operator | Second Number | Output | Is the Output Correct? |
|-------------|--------------|----------|---------------|--------|------------------------|
| 1           | 1            | +        | 1             |        |                        |
| 2           | 16           | -        | 4             |        |                        |
| 3           | 3            | *        | 5             |        |                        |
| 4           | 20           | /        | 4             |        |                        |
| 5           | 394          | +        | 1234          |        |                        |
| 6           | 1234         | -        | 7890          |        |                        |
| 7           | 0            | *        | 12            |        |                        |
| 8           | 12           | /        | 0             |        |                        |
| 9           | a            | +        | 4             |        |                        |
| 10          | 4            | <        | 12            |        |                        |

---

### Retest if Needed

| Calculation | First Number | Operator | Second Number | Output | Is the Output Correct? |
|-------------|--------------|----------|---------------|--------|------------------------|
| 1           | 1            | +        | 1             |        |                        |
| 2           | 16           | -        | 4             |        |                        |
| 3           | 3            | *        | 5             |        |                        |
| 4           | 20           | /        | 4             |        |                        |
| 5           | 394          | +        | 1234          |        |                        |
| 6           | 1234         | -        | 7890          |        |                        |
| 7           | 0            | *        | 12            |        |                        |
| 8           | 12           | /        | 0             |        |                        |
| 9           | a            | +        | 4             |        |                        |
| 10          | 4            | <        | 12            |        |                        |

---

## Deploy
1. Grade your project using the rubric below.
2. Highlight the block indicating the level you believe you achieved for each criterion.
3. Submit your assignment on Google Classroom.

---

## Maintain
- How would you expand on this project?
