# Calculator

This is a simple calculator web application built using only HTML, CSS, and JavaScript. It supports basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Addition, subtraction, multiplication, and division operations
- Clear button to reset the input
- Responsive design

## Preview

![Calculator Preview](./Screenshot%202024-05-24%20at%2012.38.23.jpg)

## Installation

No installation is required. Simply clone or download this repository and open the `index.html` file in your web browser.

## Usage

1. Open the `index.html` file in a web browser.
2. Use the calculator interface to perform basic arithmetic operations:
   - Click on number buttons to input values.
   - Click on operation buttons (`+`, `-`, `*`, `/`) to choose an operation.
   - Click the `=` button to see the result.
   - Click the `AC` button to clear the input.

## File Structure

```
calculator/
├── index.html
├── style.css
└── script.js
```

- `index.html`: Contains the HTML structure of the calculator.
- `style.css`: Contains the CSS for styling the calculator.
- `script.js`: Contains the JavaScript code to handle calculator operations.

## Code Overview

### HTML (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Calculator | ujjal</title>
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <div class="container">
      <div class="calculator">
        <input type="text" placeholder="0" id="input-box" />
        <div class="btn">
          <button class="btn-ac">AC</button>
          <button class="btn-del">DEL</button>
          <button class="btn-yellow">%</button>
          <button class="btn-yellow">/</button>
        </div>
        <div class="btn">
          <button>7</button>
          <button>8</button>
          <button>9</button>
          <button class="btn-yellow">*</button>
        </div>
        <div class="btn">
          <button>4</button>
          <button>5</button>
          <button>6</button>
          <button class="btn-yellow">-</button>
        </div>
        <div class="btn">
          <button>1</button>
          <button>2</button>
          <button>3</button>
          <button class="btn-yellow">+</button>
        </div>
        <div class="btn">
          <button>00</button>
          <button>0</button>
          <button>.</button>
          <button class="btn-grey">=</button>
        </div>
      </div>
    </div>

    <script src="./script.js"></script>
  </body>
</html>
```

### CSS (`style.css`)

```css
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap");

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "montserrat", sans-serif;
}
body {
  width: 100vw;
  height: 100vh;
  background: #000;
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
.calculator {
  width: 400px;
  height: 550px;
  border: 1px solid #fff;
  padding: 20px;
  border-radius: 1em;
  box-shadow: 0px 10px 95px #dde6ed;
}
input {
  width: 100%;
  border: none;
  color: #fff;
  padding: 25px;
  margin-bottom: 10px;
  background: #9db2bf;
  box-shadow: 0px 3px 15px rgba(86, 81, 81, 0.1);
  font-size: 40px;
  font-weight: 600;
  text-align: right;
  cursor: pointer;
  border-radius: 0.6em;
}
input::placeholder {
  color: #fff;
}
button {
  border: none;
  width: 85px;
  height: 70px;
  margin-top: 5px;
  border-radius: 5em;
  cursor: pointer;
  background: none;
  color: #fff;
  font-size: 20px;
  box-shadow: 1px 2px 2px 1px;
}
.btn-ac {
  background: #ff0000;
}
.btn-del {
  background: #f97300;
}
.btn-yellow {
  background: #526d82;
}
.btn-grey {
  background: #27374d;
}
```

### JavaScript (`script.js`)

```javascript

```
