---
title: Scale your Workflow
summary: Introduction to different tools and methods for an efficient, scalable, and maintainable workflow.
authors:
- "Markus Hofbauer"
tags:
- "Software Engineering"
- "Research"
categories:
- "Software Engineering"
- "Research"
date: "2020-05-01T15:00:00Z" # TODO correct date
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Scale your Workflow

---

## Overview

* Project Management
* Development
* Documentation

---

## Project Management

Integrated in [GitLab](https://gitlab.com)|[GitHub](https://github.com)|[Bitbucket](https://bitbucket.org)|...

* Issue Trackers
* Milestones
* Boards
* ...

---

### Issue Trackers

* Collect ideas
* Document and discuss your decisions/progress
  * For/with others
  * For/with your future self

---

![](https://pics.me.me/yes-i-talk-to-myself-thats-because-sometimes-i-need-14183709.png)

---

### Team Discussions

* Early feedback
* Constantly explain/justify/rethink your ideas

**Fail Often, Fail Fast, Fail Early**

---

## Development

---

### Implementation

* Common rules you should always follow
  * SOLID Guidelines
  * DRY (Don't repeat yourself)
* Design Patterns
  * Existing solutions for common design problems
  * Don't reinvent the wheel

---

### Testing

* Unit Tests
  * Test individual components
* Integration Tests
  * Test interaction of larger parts
* System Tests
  * Test the entire system

---

### Checks

* Consistency is key
* Automate whenever possible
* Code Format
  * Consistent code layout
  * Available for almost every language
* Linters
  * Avoid common errors

---

#### C++

* Clang-Format
* CMake-Format
* Clang-Tidy
* CppCheck
* CppLint

---

#### Python

* black
* yapf
* pylint
* flake8

---

#### Sample

```python
for t, m, ms in bag.read_messages():
    # do something
```

```shell
C0103: Variable name "t" doesn't conform to snake_case
naming style (invalid-name)

W0612: Unused variable 't' (unused-variable)
```

---

### Tools

Know your tools

* IDE for the heavy development
* Editor as your swiss army knife
* Shortcuts

---

### Version Control

* [Git](https://git-scm.com/) as most common tool
* [Git Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
* Code Review
  * Knowledge transfer in both directions

---

### Continuous Integration

* Automatically run in a configured environment
* Requires scripted/containerized environment setup
* Avoid *"Works on my machine"*

---

#### CI Failure

![](fail.jpg)

---

#### CI Pass

![](pass.jpg)

---

## Documentation

* Summarize the latest status
* Requires active maintenance

---

# Questions?
