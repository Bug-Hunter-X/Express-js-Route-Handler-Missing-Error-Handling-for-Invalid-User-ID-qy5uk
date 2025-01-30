# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  lack of error handling for invalid input.  Specifically, the code attempts to parse a user ID as an integer without checking for potential errors (e.g., non-numeric IDs). This can lead to unexpected behavior or crashes.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version with proper error handling.