# Even Or Odd Application 

This is a simple web application that lets a user determine if a number is even or odd.

## Overview
The HTML file (`even_or_odd.py`) includes a block of Python code embedded within JavaScript. When a user enters a number in the input field and clicks the "Check" button, an alert dialog displays if the number is even or odd.

## How to use

1. Open the `even_or_odd.py` file in a web browser.
2. In the input field at the bottom of the page, enter the number you want to check.
3. Click the "Check" button.
4. An alert dialog displays the result.

## Functionality

The JavaScript within the script tags in the body contains the functionality. It starts by defining the `checkEven` function which uses bitwise AND to determine if a number is even or odd.

A `loadMore` function then populates the `python-code` div with 101 lines of Python code, simulating a Python `even_or_odd` function that checks if a number is even or odd.

An IntersectionObserver monitors the `loading` div, and when this div is intersected (i.e., comes into the viewport), it calls the `loadMore` function, generating more Python code.

A click event listener waits for the "Check" button to be clicked. When it is, it gets the value of the number input field, checks if it's even or odd, and then displays an alert dialog with the result.

## Built with
- HTML
- CSS
- JavaScript
