# Interpreter
This is a learning project so I have a better understanding of how programming languages, based on Thorsten Ball's [Interpreter Book](https://interpreterbook.com/), with a follow up project planned for his [Compiler Book](https://compilerbook.com/).

## Lexer
Lexing is the first step in evaluating a programming language, in this step the code we have written is translated into tokens representing the actual meaning behind the strings of text we write for example, turning a "return" statement into tokens representing the action of returning.

Some tokens are predefined like operators, literals, and keywords. Literals represent specific values such as ints, floats, characters, and booleans. Identifiers are defined by a programmer and are references to some value, which could be literals or functions.

## REPL
A REPL or Read-Eval-Print Loop is a common tool in interpreted languages that can be used to write, evaluate, and print the results of your code. The results of a chunk of code can then be used in further chunks of code, assuming you save it to a variable or type out a returned value. An example of a REPL would be the interactive python shell.

