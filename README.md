# CSS :hover Issue with overflow: hidden

This repository demonstrates a common yet often overlooked issue in CSS concerning the interaction between the `:hover` pseudo-class and the `overflow: hidden` property on a parent container.

## Problem
When applying a hover effect (e.g., scaling) to an element within a container that has `overflow: hidden`, the effect may be unexpectedly cut off or not fully visible.  This occurs because the overflowing content is clipped by the parent's `overflow: hidden` property, even during the hover state.

## Solution
Several approaches can resolve this issue:  adjusting the parent container size, using a different technique for the hover effect, or utilizing a combination of techniques.

## Usage
Clone this repository and open `bug.html` (or open the `bug.css` and `bugSolution.css` in a browser with a corresponding HTML file) to see the buggy behavior and the solution in action.  The solution file implements one of the methods outlined in the solution section to fix the issue.