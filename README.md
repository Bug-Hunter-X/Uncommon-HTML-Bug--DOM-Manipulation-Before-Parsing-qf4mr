# Uncommon HTML Bug: DOM Manipulation Before Parsing

This repository demonstrates a subtle bug related to DOM manipulation in HTML.  The bug arises when JavaScript code attempts to interact with an HTML element before the browser has finished parsing the element. This often leads to unexpected behavior, such as the script failing silently or throwing an error.

The `bug.html` file showcases the problematic code, while `bugSolution.html` provides a corrected version.  The key is ensuring the script accessing the element executes only after the element is ready.