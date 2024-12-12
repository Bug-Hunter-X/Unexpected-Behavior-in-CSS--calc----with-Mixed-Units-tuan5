# Unexpected Behavior in CSS `calc()` with Mixed Units

This repository demonstrates a little-known quirk in CSS's `calc()` function when dealing with mixed units (percentages and other units like `em`, `rem`, `px`, etc.).  While `calc()` generally works well for simple calculations, unexpected behavior can arise when combining percentages with other units in the same expression.  This can lead to inconsistencies across different browsers and versions.

The `bug.css` file contains a CSS rule illustrating this issue, whereas `bugSolution.css` proposes solutions to handle such scenarios.