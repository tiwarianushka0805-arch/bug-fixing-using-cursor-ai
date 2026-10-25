# Bug Fixing Using Cursor AI

## Project Overview
This project demonstrates how Cursor AI can help identify and fix a logical error in a Python program that calculates the average of numbers.

## Bug Identified
The original program used `total = num` inside the loop. This replaced the total with the current number instead of adding all the numbers, resulting in an incorrect average.

## Bug Fix
The incorrect statement was replaced with `total += num`, which adds each number to the running total.

## Example
**Input:** `[10, 20, 30, 40, 50]`

**Incorrect Output:** `10.0`

**Correct Output:** `30.0`

## Technologies Used
- Python
- Cursor AI
- GitHub

## Project Files
- `buggy_average.py` — Contains the original program with the logical error.
- `fixed_average.py` — Contains the corrected program.

## Learning Outcomes
- Learned to identify logical errors in Python.
- Understood the difference between assignment and addition assignment.
- Practiced using Cursor AI to review and debug code.

## Conclusion
This project demonstrates how AI-assisted coding tools can help identify logical errors and improve the correctness of Python programs.
