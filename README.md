# Uncommon HTML Bug: innerHTML on non-existent element

This repository demonstrates an uncommon bug in HTML related to using `innerHTML` on an element that hasn't been fully parsed and added to the DOM tree.  The script attempts to modify the `innerHTML` of an element before it is fully rendered, leading to unexpected behavior.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file shows the corrected approach, ensuring proper DOM element existence before manipulation.