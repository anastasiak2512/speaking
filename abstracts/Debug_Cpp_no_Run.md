# Debug C++ Without Running

Macros, templates, compile-time evaluation and code generation, reflection and metaclasses – C++ tends to hide the final code passed to the compiler under the tons of various names and aliases. Add here the preprocessor that shadows the actual running curve of your program with dozens of alternatives mixed in a non-trivial way. While this allows to avoid boilerplate code and reduce copy-paste and other errors, such an approach demands better tooling support to make the debugging process easier.

To find an error in such a code, one has to continuously read-fix-run it and compare the results with some etalon, or to debug in order to find actual substitutions. But should you really wait until your code is run or even compiled to debug it? Or how to deal with the situations when the code can’t be run on the local machine? A text editor with code completion won’t help, while a smart IDE that “gets” your code can do a better job.

In this talk we’ll see interesting approaches to solving cases like macro and typedef ‘debug’, understanding types when auto/decltype hide them, dealing with different code branches depending on the preprocessor’s pass-through, and other ideas. The aim of this talk is to share the workflows supported by the tools that can help C++ developers create better modern C++ code.
