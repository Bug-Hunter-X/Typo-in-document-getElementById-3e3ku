# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle error that can easily be overlooked in HTML and JavaScript interaction.  The error involves a simple typo in the widely used `document.getElementById` method.

## The Bug

The `bug.html` file contains a typo in the JavaScript code. Instead of correctly using `document.getElementById`, it uses `document.getElementByIdx`. This will result in a runtime error because `getElementByIdx` is not a defined method.

## The Solution

The `bugSolution.html` file corrects the typo, ensuring the code now correctly accesses and manipulates the DOM element.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.  You should see a runtime error in the browser's console.
3. Open `bugSolution.html` to see the corrected code working as expected.