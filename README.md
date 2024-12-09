# CSS :checked Pseudo-class Usage Error

This repository demonstrates a common error when using the `:checked` pseudo-class in CSS to style labels associated with checkboxes.  The provided `bug.css` file contains the incorrect implementation.  The corrected version is in `bugSolution.css`.

The error arises from an incorrect understanding of how the `:checked` selector interacts with sibling elements.  It cannot be directly applied to the label element; instead, it must be used with the general sibling combinator (+) to select the label that is immediately preceded by the checkbox.