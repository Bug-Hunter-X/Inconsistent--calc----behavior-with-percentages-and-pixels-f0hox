# Inconsistent `calc()` behavior with percentages and pixels

This repository demonstrates an uncommon issue related to the `calc()` function in CSS when combining percentages and fixed units (like pixels).  In certain situations, the expected calculation might not produce the correct result, leading to layout inconsistencies.

The `bug.css` file showcases the problematic code.  The `bugSolution.css` file provides a potential workaround or clarification on how to correctly use `calc()` in similar situations.  This might involve using different units or alternative layout techniques.

This issue is subtle and might not be easily reproduced or noticed in all cases. It's important to be aware of potential limitations and edge cases when working with `calc()` to prevent unexpected rendering behaviors.