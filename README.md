# Interpreter in C

Maintained by **Derek Ko**.

A tree-walk interpreter for the Lox language, implemented in C. It includes
lexical analysis, recursive-descent parsing, lexical scope resolution, and
runtime evaluation.

## Features

- Expressions, variables, conditionals, and loops
- Functions, closures, and return values
- Classes, instances, inheritance, `this`, and `super`
- Separate commands for tokenizing, parsing, evaluating, and running programs

## Build and run

Requires CMake 3.13+ and a C compiler with C23 support.

```sh
./your_program.sh run demo.lox
./your_program.sh tokenize demo.lox
```

For a direct build:

```sh
cmake -S . -B build-local
cmake --build build-local
./build-local/interpreter run demo.lox
```

This is an experimental language implementation. The source currently lives
in `src/main.c`.
