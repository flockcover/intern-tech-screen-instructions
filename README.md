# Flock Tech Screen
In a language of your choice, please write a program which accepts as input two arbitrarily nested arrays of strings, and returns the sum of the number of necessary one character substitutions multiplied by 2 to the power of the depth of nesting at which substitution must occur

For example:

```
yourFunction(
["I", ["love"], [[["awesome", "shiny"]]], "drones"],
["I", ["hate"], [[["magenta", "dirty"]]], "drains"]
)
``` 
should return `2(3) + 8(7 + 4) + 3 = 97`

If the levels of nesting or the lengths of the strings do not match, return `-1` so:
`yourFunction(["I", ["love"], [["awesome"]], "drones"], ["I, ["hate"], [[["magenta"]]], "drains")` should return `-1`

If the lengths of any fragment differ, return `-1` so:
`yourFunction(["I", ["adore"], [[["red"]]], "drones"], ["I, ["hate"], [[["magenta"]]], "drains")` should return `-1`


## Submission guidelines
- Please ensure that your submission is runnable. Bonus points if your code is tested.
- Submit your code either as a Zipfile including a document answering the questions outlined below and your code,
or as a link to a Version Control System of your choice. Bonus points for the latter
- In addition to your code, please submit a brief document (as a README or otherwise), answering the following questions:
  1) What assumptions did you make?
  3) What is the Big O of your solution? Please justify your answer.
  3) In what ways do you feel your code could be improved?
  4) What tests (if any) have you written? What tests do you feel you could still write?
  5) How do we run your code. Please be aware that we may not have your programming environment installed. Unless you are submitting a compiled binary with your code, please provide instructions on what to install and how.
