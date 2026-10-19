# debug_log.md
# Author: Juan Poveda

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 12
What the error means: Python tried to get a key from a dictionary, and the dictionary does not have that key.
What I told the duck: When I read Taylor's record out loud, I noticed the key was spelled 'amout', so that record has no 'amount' key.
How I fixed it: I changed the typo 'amout' to 'amount' in Taylor's record so all three records use the same key.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means: Python can't compare two different types with >. total is an int, but '1000' is a string, so the comparison fails.
How I fixed it: I removed the quotes so the line reads return amount > 1000, which compares a number to a number.

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? No
If yes -- exact prompt I used: ___
What AI explained: ___
What I changed myself: ___
Can I explain every fixed line? Yes / No

## What I learned
I learned to read a traceback from the bottom up, because the last line tells you the error type and the line above it shows exactly where the code broke. I also learned that a KeyError usually means a typo in the data, and a TypeError means you are mixing types, like comparing a number to a string.