---
title: "Sample Compiler"
excerpt_separator: "<!--more-->"
categories:
  - Projects
tags:
  - Projects
  - Grand Canyon University
---

A sample compiler developed as the focus of GCU course CST-405: "Principles of Compiler Design". Compilation is separated into 6 phases...
- **Lexical Analysis:** Source code is tokenized.
- **Parsing:** Tokenized code is arranged into an abstract syntax tree (AST).
- **Semantic Analysis:** AST is checked for potential syntax errors.
- **Intermediate Code Generation:** Three-address code (TAC) instructions are generated from the structure of the AST.
- **Code Optimization:** Redundant TACs are eliminated, improving the intermediate code (e.g. unnecessary memory operations).
- **Target Code generation:** Code for target language is generated from optimized TACs. In this compiler's case, the target code is assembly.

Project was assigned by Dr. Isac Artzi. The compiler was written in collaboration with Evan Lloyd, a fellow GCU alumnus.

[The repository for the final submission can be located here.](https://github.com/SpencerM-2k1/CST-405-Compiler-Final)