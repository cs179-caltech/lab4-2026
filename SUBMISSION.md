# Run command

Write commands that compile your code and runs the `checker.py`s. Make sure the reference executables included in the repo work when running your commands.

First, output the `scan` checker output, then `find_repeats` checker output, then `render`.

The output when running these commands include the test results for `scan`, `find_repeats`, and `render`. Example:
```
# checker.py scan
Test: scan

--------------
Running tests:
--------------

Element Count: 1000000
Correctness passed!
# ... more details on scan tests ...


# checker.py find_repeats
Test: find_repeats

--------------
Running tests:
--------------

Element Count: 1000000
Correctness passed!
# ... more details on find_repeats tests ...


# checker.py for render
Running scene: rgb...
[rgb] Correctness passed!
# your numbers will be different
[rgb] Student times:  [0.1234, 0.1234, 0.1234]
[rgb] Reference times:  [0.1234, 0.1234, 0.1234]
# plus many more scenes
```

The TA grading your set will run these commands. Make sure they work! Also don't reference files outside of your submission directory. The TA will only see files included in your submission zip.

Commands to check:
```bash
# TODO
```

# Writeup

TODO