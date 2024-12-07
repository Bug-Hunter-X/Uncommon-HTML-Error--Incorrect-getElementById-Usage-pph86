# Uncommon HTML Error: Incorrect getElementById Usage

This repository demonstrates a common mistake when using the `document.getElementById()` method in JavaScript within an HTML file.  The error arises from including the '#' symbol before the element's ID, which is unnecessary and prevents the function from correctly identifying the element.

## Bug
The `bug.html` file contains the erroneous code that attempts to select an element with the ID 'myDiv' using `document.getElementById('#myDiv')`. This will return `null` because the '#' symbol is not part of the getElementById() syntax.

## Solution
The `bugSolution.html` file provides the corrected code which selects the element correctly using `document.getElementById('myDiv')`.