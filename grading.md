---
layout: single-page-md
title: APIO 2021 Grading System
key: grading
---

An instance of [Contest Management System (CMS)](http://cms-dev.github.io/) modified for APIO 2021 will be used as the grading system.

**Machine**

- TBA

**Compiler**

The exact commands used for compilation will be shown on the grading system. With the exception of certain task types, the compilation command will generally be of the following format:

- C++ (gcc 9.3.0): `/usr/bin/g++ -DEVAL -std=gnu++17 -O2 -pipe -static -s -o ${task} grader.cpp ${task}.cpp`
