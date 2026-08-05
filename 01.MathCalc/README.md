# MathCalc
This is a math calculator. Strings are passed via an environment var in a special format:
```10,add,20```
Possible operators:
 - add
 - subtract
 - multiply
 - divide

Then print the answer. The only thing that should be printed is the answer.
For example `1,add,3` would output 4, and `2,multiply,3` should output 6. If the operator is invalid, raise a ValueError.
