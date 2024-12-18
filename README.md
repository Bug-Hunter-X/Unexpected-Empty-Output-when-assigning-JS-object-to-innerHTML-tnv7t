# Uncommon HTML Bug: Object Assignment to innerHTML

This repository demonstrates an unusual issue in HTML where assigning a JavaScript object directly to the `innerHTML` property of an element leads to an unexpected empty output instead of the expected string representation.

The `bug.html` file contains the erroneous code.  The `solution.html` file offers a corrected version.

This demonstrates a subtle misunderstanding of how innerHTML interacts with data types.  The solution involves converting the object to a string before assignment.