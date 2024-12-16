# PHP Loose Comparison Pitfall

This repository demonstrates a common, yet easily overlooked, issue in PHP: the loose comparison operator (`==`).  When comparing values of different types, PHP's loose comparison can lead to unexpected results due to type coercion.

The example highlights the problem with comparing strings and numbers. The solution offers a safer approach using the strict comparison operator (`===`)

## Bug
The `bug.php` file shows the problematic code where a string '1' is compared to the integer 1 using the loose comparison operator. 

## Solution
The `bugSolution.php` file provides a corrected version using the strict comparison operator (`===`) to prevent type coercion and ensure accurate comparisons.