# CSS `calc()` Gotchas: Operator Precedence and Units
This repository demonstrates common errors encountered when using the `calc()` function in CSS, specifically focusing on operator precedence and unit consistency.  The `bug.css` file showcases problematic code, while `bugSolution.css` presents the corrected version.

**Key Issues Addressed:**

* **Incorrect Operator Precedence:**  `calc()` follows standard mathematical operator precedence.  Without parentheses, unexpected results can occur.
* **Missing or Inconsistent Units:** Every value within `calc()` must have a unit (e.g., px, %, em).  Omitting units or mixing units without proper conversion will cause errors.

**How to Use:**

1. Clone the repository.
2. Open `bug.css` to see the problematic code.
3. Compare it to `bugSolution.css` to understand the corrections.
4. Experiment with the code to grasp the intricacies of `calc()`.