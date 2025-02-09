# Uncommon HTML Error: Incorrect Method to Access Elements

This repository demonstrates a subtle error in accessing HTML elements using JavaScript. The error involves a misspelling in the `getElementById` method, resulting in unexpected behavior.

## Bug Description

The `bug.html` file contains a simple HTML page with a paragraph inside a div. The JavaScript code attempts to change the inner HTML of the div element. However, there's a typo in the `getElementById` method (it is written as `getElementByIdx` which is incorrect). This will not throw an error but will result in the inner HTML remaining unchanged.

## Bug Solution

The `bugSolution.html` file demonstrates the corrected code where the typo is fixed, correctly changing the inner HTML of the div element.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` in your web browser.
3. Observe the content.  The text within the div should not change.
4. Then open `bugSolution.html`, the content within the div should be changed successfully.
