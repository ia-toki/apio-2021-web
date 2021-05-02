---
layout: single-page-md
title: APIO 2021 Grading System
key: grading
---

An instance of [Contest Management System (CMS)](http://cms-dev.github.io/) modified for APIO 2021 will be used as the grading system.

**Machine**

Grading will be performed on Amazon Web Services' c5.metal Elastic Compute Cloud (EC2) instances with the following specifications:
- OS: Ubuntu 20.04
- Processor: Intel(R) Xeon(R) Platinum 8275CL
  - Clock speed set to 2.7 GHz (Intel® Turbo Boost Technology disabled)
  - Hyper-threading disabled
  - 2 cache ways of the L3 cache dedicated to each CPU core used for grading
- Each execution of a submission will be assigned to a separate physical CPU core

**Compiler**

The exact commands used for compilation will be shown on the grading system. With the exception of certain task types, the compilation command will generally be of the following format:

- C++ (gcc 9.3.0): `/usr/bin/g++ -DEVAL -std=gnu++17 -O2 -pipe -static -s -o ${task} grader.cpp ${task}.cpp`
