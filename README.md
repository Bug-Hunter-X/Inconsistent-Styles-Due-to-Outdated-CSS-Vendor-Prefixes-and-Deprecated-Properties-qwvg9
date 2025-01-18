# Inconsistent Styles Due to Outdated CSS Vendor Prefixes and Deprecated Properties

This repository demonstrates a common yet subtle issue in CSS: the use of outdated vendor prefixes and deprecated properties. These can lead to inconsistent rendering across different browsers and often go unnoticed unless thoroughly tested.

The `bug.css` file contains the problematic CSS.  `bugSolution.css` provides a corrected version.

## Bug:
The primary issue lies in using unnecessary vendor prefixes and a deprecated property resulting in inconsistent rendering between browsers.

## Solution:
The solution involves removing the obsolete prefixes and replacing the deprecated property with its modern equivalent.  Always keep your CSS up-to-date with the latest specifications to avoid these problems.