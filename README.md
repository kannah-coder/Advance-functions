# Advance-functions
# JavaScript Functions & Event Listeners (Practice)

This repo is just me practicing JavaScript basics like functions, anonymous functions, arrow functions, and event listeners.

## What I did here
- Normal function
- Function stored inside variable
- Anonymous function
- Passing values (parameters)
- Passing a function inside another function
- Arrow function
- `addEventListener` and `removeEventListener`
- Multiple listeners on the same button

##  Demo
- Button click logs different messages in the console.
- Shows how to remove event listeners properly (by storing the function in a variable first).
- Example of using `onclick` vs `addEventListener`.

## Notes
- Functions are values in JS → can be stored in variables, passed as parameters, etc.
- To remove an event listener → **must use the same reference of the function** (that’s why I stored arrow function in `a`).
- Good reminder: anonymous functions can’t be removed since they don’t have a reference.

##  Run
Just open `index.html` in browser and check **console** (F12 → Console).
