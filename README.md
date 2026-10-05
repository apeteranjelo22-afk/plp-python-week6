# Week 6 Error Handling Assignment

This Assignment practices Python error handling using `try` and `except`.

* `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary lookups.
* `unbreakable.py` - Contains the second part of the Week 6 error-handling assignment. There are no codes to be run in this section.

An `if` check cannot capture `abc` by itself because `abc` is a string and the error happens when Python tries to convert it into an integer with `int()`. The `ValueError` occurs during the conversion, so `try` and `except ValueError` are needed to handle it safely.
