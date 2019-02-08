+++ 
title = "Tidbit 0: Function Declaration vs. Function Expression in JavaScript"
date = 2019-01-05T06:29:19-05:00
tags = ["function declaration", "function expression", "javascript", "tidbit"]
categories = ["function declaration", "function expression", "javascript", "tidbit"]
draft = false
+++

*Tidbit is a series of (hopefully) short and sweet explanations of certain ideas and topics across computer science. Since large tutorials takes time to write, I will fill the time with tidbits which can act as pocket guides to help remind you of certain concepts. These will be released out of order as I am just taking these from my notes randomly when I am reviewing.*

# Two Ways of Writing a Function

In Javascript there are two ways to write a function:

## Function Declaration

```javascript
function add(num1, num2) {
    return num1 + num2;
}
```

and

### Function Expression

```javascript
let add = function(num1, num2) {
    return num1 + num2;
}
```

# Hoisting: The Differentiator

The difference between the two function types is the idea of hoisting. Hoisting is just a fancy way of saying that something is available or known before any code is run. 

What this means behind the scenes is that function declarations and variable declartions are added to memory during compilation.

## What Works

```javascript
function add(num1, num2) {
    return num1 + num2;
}

add(2, 2); // returns 4
```

and

```javascript
add(2, 2); // returns 4

function add(num1, num2) {
    return num1 + num2;
}
```

## What Does Not Work

```javascript
add(2, 2) // returns Uncaught TypeError: add is not a function

let add = function(num1, num) {
    return num1 + num2;
}
```