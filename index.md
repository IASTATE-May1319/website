---
layout: base
title: Senior Design Group 19
summary: Main page
---

## Project Description

Current type checking software is able to locate code that violates a given rule, but the software is extremely limited in its ability to provide evidence as to why the rule was violated. Knowing why a rule was violated is the first step in creating a viable solution or preventing code from violating the rule again in the future. Additionally, current type checking software can return bloated results for a rule violation, making it difficult to locate the exact portion of code causing the violation.

There is a need for a type checking software that:

* Leverages an existing analysis framework so that a complex tool can be built within a year as opposed to several years of effort (referencing the University of Washington Checker Framework project that this software is intended to improve upon)
* Provides useful approximate analysis (as the exact program analysis is known to be intractable)
* Provides powerful analysis capabilities incrementally, by refining the approximate analysis.

