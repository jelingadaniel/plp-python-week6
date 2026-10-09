# PLP Python Week 6 - Safe Functions

## Files

* `safe_tools.py` — Contains three safe functions for division, converting text to integers, and looking up dictionary fields.
* `README.md` — Describes the assignment files and explains error handling.

## Why can't an if check catch "abc" on its own?

An `if` statement can check a condition, but it does not automatically handle errors raised when converting text to an integer. For example, `int("abc")` raises a `ValueError`, so using `try` and `except ValueError` allows the program to handle invalid input safely instead of crashing.
