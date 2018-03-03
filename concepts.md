This list is taken from https://medium.com/@saulpw/martial-arts-belts-for-software-developers-a9ee82c3422b and is rather C-focused.
I'm still using it as an inspiration for "basic concepts that might be important/necessary".

## White Belt

* sequential operation
    * `.` separates expressions ("as in the English language")
    * `;` separates messages to the same object ("cascade")
* comments
    * either within quotes `"..."` or in a specific input field in the IDE.
* local variables (identifiers), assignment
    * `| localVar |`, `localVar := 'this value'`.
* mathematical expressions (incl. operator precedence review)
    * there is no precedence. everything is evaluated left to right.
* output of numbers
    * have not yet stumbled upon Smalltalk formatstrings.

## Yellow Belt

* functions, parameters and return values, calling of
    * works through messages and their selectors
* cmdline input
    * TODO
* conditional statements: if, for/while/do loops, switch
    * not part of the core language
    * `<expression> ifTrue: [...] ifFalse: [...]`
    * loops and switch: TODO
* alternate control flow: early return, continue/break
* error checking (for no args), early exit
* string constants (backslash escapes)
* global variables
