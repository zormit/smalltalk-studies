* Transcript
    * Something similar to "stdout", will be shown in the Launcher.
    * "Transcript is an instance of class TextCollector, and so displays string data."
    * `TextCollector cr` -- prints a newline character.
        * by sending it to its instance variable `entryStream`, which is a `WriteStream`
        * `Stream` has them implemented `cr` as `self nextPut: Character cr`
        * `cr` is defined in `Characters` as `13`, which is the decimal in ASCII for `\n`
    * `Transcript show: 'this string'` -- prints `this string`.
