# Unexpected behavior of calc() in CSS due to spaces around operators

This repository demonstrates an uncommon issue with the `calc()` function in CSS.  Spaces around the arithmetic operators (+, -, *, /) within the `calc()` function can lead to unexpected results or parsing errors.  The provided CSS file (`bug.css`) shows the problematic code, while the solution (`bugSolution.css`) demonstrates how to correct it.

This issue is subtle and can be difficult to debug. This example highlights the importance of paying close attention to whitespace within CSS calculations.

## How to reproduce

1. Open `bug.html` in a web browser.
2. Observe that the element's width is not calculated correctly. 
3. Open `bugSolution.html` in a web browser to see the corrected output.