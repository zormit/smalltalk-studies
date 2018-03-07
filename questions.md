WalkThrough
* pg 45: ^self defaultGeneratorClass new
    * does this send the _value_ of defaultGeneratorClass to self?


Wikipedia
* code blocks: understand if implementation.
* Classes: is this now a instanceVariableNames:classVariableNames:poolDictionaries:category: selector?


* Help! My "HelloWorld" image seems to be broken. How to debug?
* How to disassemble VisualWorks Smalltalk bytecode?

* How do I find a method in a class hierarchy?
    * e.g. I was looking for `cr` in `WriteStream`, but it is implemented in `Stream`.
* How can I read from `Stdin`?
* Sh*t, I'm always loosing my method definitions. Is my workflow wrong?
* I thought execution is from left to right, but there seems to be no difference in:
    * `Transcript cr; show: (sequence size printString).` vs.
    * `Transcript cr; show: sequence size printString.`
        * ok here we have a differing example:
            * `aNumber abs sqrt + (5 * (aNumber ** 3)).` != `aNumber abs sqrt + 5 * aNumber ** 3.`
