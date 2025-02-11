# Incorrect Usage of textContent in HTML

This repository demonstrates a subtle bug related to the use of `textContent` and `innerHTML` when updating the content of HTML elements.

## The Bug
The `bug.html` file shows incorrect usage of `textContent`. When you want to modify a div that contains inner HTML elements, `textContent` will overwrite the existing HTML.  The solution showcases the correct approach. 

## The Solution
The `bugSolution.html` file provides the correct solution, demonstrating the proper usage of `innerHTML` to modify HTML elements without losing the existing structure. 

## How to reproduce the bug
1. Open `bug.html` in a web browser.
2. Observe that the text content of the div is changed, but not as expected.

## How to fix the bug
1. Open `bugSolution.html` in a web browser.
2. Observe that `innerHTML` correctly replaces the content, maintaining the structure.