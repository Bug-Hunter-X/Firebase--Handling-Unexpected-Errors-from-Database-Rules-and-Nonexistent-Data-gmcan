# Firebase: Unexpected Errors from Database Rules and Nonexistent Data

This repository demonstrates a common, yet often difficult to diagnose, error encountered when using the Firebase Realtime Database: unexpected errors arising from overly restrictive security rules or attempts to access non-existent data.

The `firebaseBug.js` file shows example code that leads to such errors.  The `firebaseBugSolution.js` file presents solutions and best practices to mitigate these issues.

## Setup:

1.  Initialize a Firebase project.
2.  Install the Firebase JavaScript SDK: `npm install firebase`
3.  Configure your Firebase project in `firebaseBug.js` and `firebaseBugSolution.js` with your project's credentials.
4.  Set appropriate security rules in your Firebase console.

## Running the Code:

Run `firebaseBug.js` to reproduce the error. Then, run `firebaseBugSolution.js` to see how to fix the issue.