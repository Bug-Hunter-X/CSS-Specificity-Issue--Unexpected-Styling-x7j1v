# CSS Specificity Bug

This repository demonstrates a common CSS issue related to selector specificity.  The bug involves a CSS rule that's too broad, affecting elements unintentionally.  The solution shows how to improve specificity to target only the intended elements.

## Bug

The `bug.css` file contains a CSS rule that applies a blue color to paragraph elements (`<p>`) within a container element (`.container`).  However, due to the lack of specificity in the selector, this rule also applies to paragraphs nested within other elements inside the `.container`.

## Solution

The `solution.css` file demonstrates a solution to fix this specificity problem.  The approach taken is to increase the specificity of the selector to ensure it only applies to the intended paragraphs.