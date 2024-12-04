# README: JavaScript Tasks Solution

This README file describes the tasks and their solutions for implementing JavaScript concepts using prompts, loops, functions, and objects.

---

## Task 1: Welcome Alert and Personalized Greeting
### Description
- The script welcomes the user to the site and asks for their name and favorite color (red, green, or blue).
- It displays a personalized greeting (`Welcome [name]`) in the chosen color.

### Functionality
1. **Alert**: Displays a welcome message: `"Welcome to my site"`.
2. **Prompt for Name**: Asks the user for their name.
3. **Prompt for Color**: Prompts the user to choose a color from `red`, `green`, or `blue`.
4. **Output**: Writes `Welcome [name]` to the page in the selected color.

### Implementation Notes
- The script validates the chosen color and applies it to the text dynamically using inline CSS.

---

## Task 2: Display Message Using HTML Headings
### Description
- The script takes a message from the user and displays it using all HTML heading tags (`<h1>` to `<h6>`).

### Functionality
1. Prompts the user to enter a message.
2. Uses a loop to generate headings from `<h1>` to `<h6>` dynamically.
3. Displays the message inside each heading tag.

### Implementation Notes
- No hardcoded heading elements are used in the script.
- The headings are created programmatically using loops.

---

## Task 3: Sum of Entered Numbers
### Description
- The script calculates the sum of numbers entered by the user.
- It stops receiving inputs when:
  - The user enters `0`, or
  - The sum exceeds `100`.

### Functionality
1. Uses a `do-while` loop to repeatedly prompt the user for numeric input.
2. Checks if the entered value is numeric. If not, an error message is displayed.
3. Stops when the user enters `0` or the total sum exceeds `100`.
4. Displays the total sum of all valid inputs.

### Implementation Notes
- Includes validation for numeric input.
- Alerts the user with the final total sum when the loop ends.

---

## Functions

### 4.1 Function with Parameter Count Validation
- **Description**: A function that accepts exactly two parameters.
- **Functionality**:
  - Throws an exception if the number of parameters is less than or greater than two.
  - Demonstrates error handling with `try-catch` blocks.

---

### 4.2 Function to Add Multiple Values
- **Description**: A function to add an arbitrary number of parameters, ensuring all are numeric.
- **Functionality**:
  - Iterates through the parameters to check if each is a number.
  - Returns the sum of valid parameters.
  - Throws an exception for non-numeric parameters.

---

## Object: Rectangle

### Description
- A script to create a `Rectangle` object with `width` and `height` properties.

### Features
1. **Properties**:
   - `width`: Width of the rectangle.
   - `height`: Height of the rectangle.
2. **Methods**:
   - `calculateArea()`: Returns the area (`width * height`).
   - `calculatePerimeter()`: Returns the perimeter (`2 * (width + height)`).
   - `displayInfo()`: Logs a message with the rectangle's dimensions, area, and perimeter.
3. **Usage**:
   - The script demonstrates the object creation and method calls.

---

## How to Run
1. Copy the JavaScript code into a `.js` file or directly into your browser's developer console.
2. Attach the script to an HTML file using the `<script>` tag.
3. Open the HTML file in a browser to execute the tasks.

---

Enjoy exploring the solutions! 😊
