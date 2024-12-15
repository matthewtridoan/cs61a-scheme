# CS61A: Scheme

This repository contains the implementation of the [Scheme](https://cs61a.org/proj/scheme/) project for UC Berkeley's CS61A course. Scheme is a dialect of Lisp and is known for its simplicity, elegance, and powerful functional programming features.

## Project Overview

This project implements an interpreter for the Scheme programming language. The interpreter is written in Python and consists of multiple modules that handle various aspects of the language, including parsing, evaluation, and built-in procedures.

### Key Concepts

- **Evaluation Model**: The interpreter follows Scheme's evaluation model, where expressions are recursively evaluated in the context of environments.
- **Input Parsing**: The interpreter handles complex inputs through an eval-apply process.

## Repository Structure

```
cs61a-scheme/
├── scheme.py             # Main entry point of the interpreter
├── pair.py               # Implements the `Pair` class, which represents Scheme's fundamental pair structure, used to build lists and other compound data structures.
├── scheme_builtins.py    # Defines the built-in functions and special forms available in Scheme, such as arithmetic operations, list manipulation functions, and more.
├── scheme_classes.py     # Contains additional classes and structures used in the interpreter, such as environments and frames for variable scope and binding.
├── scheme_eval_apply.py: # Implements the core evaluation and application logic of the interpreter. This includes evaluating Scheme expressions and applying functions.
├── scheme_forms.py:      # Defines the handling of special forms in Scheme, such as `define`, `lambda`, `if`, and `quote`.
├── scheme_tokens.py:     # Handles lexical analysis and tokenization of Scheme source code.
├── scheme_utils.py:      # Provides utility functions used throughout the project, including error handling, debugging aids, and helper methods.
├── tests/                # Directory containing test files
├── abstract_turtle/      # Handles opening the python turtle from the interpreter
└── README.md             # Project overview and instructions (this file)
```

## Getting Started

### Prerequisites

To run the project, you'll need Python 3.6 or later. Install it from the [official Python website](https://www.python.org/downloads/).

### Installation

Clone the repository:

```bash
git clone https://github.com/matthewtridoan/cs61a-scheme.git
cd cs61a-scheme
```

### Running the Interpreter

To run the Scheme interpreter:

```bash
python scheme.py
```

## Contributing

Contributions are welcome! If you'd like to make changes or improvements, feel free to fork the repository, make your changes, and submit a pull request.

## Acknowledgments

- **UC Berkeley CS61A Team**: For creating this fantastic project.
- **John DeNero**: Instructor of CS61A, whose materials inspired this implementation.
- [CS61A Official Website](https://cs61a.org/): Course resources and materials.
