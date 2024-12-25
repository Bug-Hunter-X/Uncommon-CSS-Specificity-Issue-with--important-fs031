# Uncommon CSS Specificity Issue

This repository demonstrates an uncommon issue related to CSS specificity and the use of the `!important` declaration.  The issue involves unexpected behavior when a highly specific selector overrides a selector with the `!important` declaration.  This can lead to difficult-to-debug issues in larger CSS projects.

## Bug Description

A seemingly simple inheritance and specificity problem in CSS that demonstrates how `!important` can be superseded. The primary goal is to create a clear demonstration of how this unexpected interaction occurs and to provide a solution to correct the behavior.

## How to reproduce

1. Clone this repository
2. Open `bug.css` to observe the problem. 
3. Open `bugSolution.css` to observe the solution.
4. Observe the results using any web browser.