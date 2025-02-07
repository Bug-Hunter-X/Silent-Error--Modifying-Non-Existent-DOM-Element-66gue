# Silent Error: Modifying Non-Existent DOM Element

This repository demonstrates a common, yet often silent, error in HTML/JavaScript: attempting to modify the content of a DOM element that does not exist.  This can lead to unexpected behavior without any clear error messages.

## Bug Description
The `bug.html` file contains a script that tries to change the `innerHTML` of an element with the ID "nonExistentDiv".  Since this element doesn't exist in the HTML, the script fails silently.

## Solution
The `bugSolution.html` file demonstrates the correct way to handle this situation, by first checking if the element exists before attempting to modify its content.