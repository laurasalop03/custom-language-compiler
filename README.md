# C++ Compiler Engine & Abstract Syntax Tree (AST)

_Developed for the Language Processors course (Procesadores del Lenguaje, 2025-26), Computer Science and Mathematics double degree, University of Granada._

A custom language compiler and parsing engine built from scratch to demonstrate low-level systems engineering, formal grammar validation and memory-safe execution.

### Tech Stack
C/C++, Flex (Lexical Analyzer), Bison (Syntax Analyzer).

### Algorithmic & Systems Highlights
* **Lexical & Syntactic Analysis:** Engineered a deterministic finite automaton (DFA) pipeline to tokenize raw string inputs and validate complex grammar rules under strict time and memory constraints.
* **AST Construction & Traversal:** Built and optimized an Abstract Syntax Tree to manage hierarchical execution logic. Enforced strict C++ memory management to prevent leaks during recursive tree traversals and node evaluations.
* **Algorithmic Correctness:** Designed the parsing engine to handle edge cases, syntax errors, and ambiguous grammar inputs gracefully, ensuring predictable and deterministic code execution.
