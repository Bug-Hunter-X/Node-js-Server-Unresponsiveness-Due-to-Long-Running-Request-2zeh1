# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js servers: unresponsiveness caused by long-running synchronous operations in request handlers.  The `server.js` file contains a server that simulates a long-running task, blocking the event loop and preventing it from handling subsequent requests.  This leads to the server appearing to hang or become unresponsive.

The solution (`serverSolution.js`) demonstrates how to address this issue using asynchronous programming techniques, ensuring that the server remains responsive even during lengthy operations.