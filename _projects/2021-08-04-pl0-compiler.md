---
layout: project
title: PL/0 Compiler
image: roundabout.jpg
image_alt: A picture of a roundabout
---

## Overview
A compiler for the PL/0 language, made as a group project for the Systems Software class at UCF in Summer 2021.

### Design
The compiler has two parts: a lexical analyzer and a parser / code generator. A pl/0 program is first processed by the lexical analyzer, which breaks the program into tokens. The tokens then go into the parser / code generator, which generates "machine code". We also made a virtual machine to run the generated code.

### Links
- [Source code][repo]

[repo]: https://github.com/msabur/pl0-compiler
