# React Native: Uninitialized State/Prop Access

This repository demonstrates a common React Native error: accessing state or props before they have been initialized. The error typically occurs when asynchronous operations (e.g., data fetching) are involved.  The `Bug.js` file shows the erroneous code. `BugSolution.js` provides the corrected version using techniques like conditional rendering and the optional chaining operator.

## Setup

1. Clone the repository.
2. `npm install` or `yarn install`
3. Run the app using your preferred React Native method.

## How to reproduce the error:

Run `Bug.js` - You should see a crash related to undefined property access.

## Solution:

Refer to `BugSolution.js` for a solution that uses conditional rendering and optional chaining to gracefully handle the case where the state/props haven't been initialized yet.