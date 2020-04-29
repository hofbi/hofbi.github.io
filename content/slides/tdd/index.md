---
title: Test Driven Development
summary: General Introduction to Unit Tests and Test Driven Development
authors:
- me
tags:
- "C++"
- "SOLID"
- "Software Engineering"
categories:
- "Software Engineering"
date: "2020-01-16T15:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Test Driven Development

[Code](https://github.com/hofbi/tdd-sample)

---

## Unit Tests

* Separate (non production) program/code to test your code
* Test your code on the lowest (unit) layer
* General 3 step structure of a unit test
  * **Given**: Setup unit and environment
  * **When**: Execute unit to test
  * **Then**: Test for expected result

---

### Why Tests

Michael Feathers, Working Effectively with Legacy Code

> “To me, legacy code is simply code without tests.”

---

## TDD

* Write your test before your production code
* 3 Phases
  * **Red Phase**: Define a failing test
  * **Green Phase**: Fix that test (Solve Simple)
  * **Refactoring**: Clean up your code

---

<img src="https://angularjsbeginnerguide.files.wordpress.com/2017/01/tdd.jpg" alt="TDD Workflow" height="500"/>

---

## FizzBuzz Task

Write a function that returns the number it was given or *Fizz* if it is multiple of 3, *Buzz* if it is multiple of 5 or *FizzBuzz* if it is multiple of both.

[C++](https://github.com/hofbi/tdd-sample#cpp) | [Python](https://github.com/hofbi/tdd-sample#python)

---

## Task Definition

1. Can call function `fizzBuzz`
1. Return 1 for 1
1. Return 2 for 2
1. Return Fizz for 3
1. Return Buzz for 5
1. Return Fizz for 6
1. Return Buzz for 10
1. Return FizzBuzz for 15

---

# Questions?

[Try yourself](https://github.com/hofbi/tdd-sample)
