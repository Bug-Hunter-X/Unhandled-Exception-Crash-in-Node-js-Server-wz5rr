# Unhandled Exception in Node.js Server

This repository demonstrates an example of a Node.js server crashing due to an unhandled exception. The `bug.js` file contains the problematic code, which throws an error without proper handling.  The `bugSolution.js` demonstrates a corrected version with proper error handling.

## Bug
The server crashes when the `/error` route is accessed, because the thrown error isn't caught.

## Solution
The solution involves using a `try...catch` block to handle the potential error and gracefully respond or log the error without crashing the server.