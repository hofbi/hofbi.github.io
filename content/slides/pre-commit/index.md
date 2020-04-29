---
title: Everything to know about pre-commit
summary: General Introduction to pre-commit
authors:
- admin
tags:
- "Software Engineering"
- "pre-commit"
categories:
- "Software Engineering"
date: #"2020-01-16T15:00:00Z"
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Everything to know about `pre-commit`

---

## Automate whenever possible

* Guidelines
* Code format
* Static code analysis
* ...

---

## How to manage all these tools

* Shell scripts for every tool?
* Makefiles or similar frameworks?
* Git hooks calling the scripts?

---

## Drawbacks

* Script/tool maintenance
* Tooling setup/dependencies
* Forgot to run the checks locally

---

## `pre-commit`

> A framework for managing and maintaining multi-language pre-commit hooks

[pre-commit.com](https://pre-commit.com/)

---

### Features

* Automatically setup all dependencies in virtual environments without root access required
* Manage all tools in a single configuration file `.pre-commit-config.yaml`

---

### Configuration

```yaml
default_stages: [commit]
repos:
  - repo: https://github.com/pre-commit/pre-commit-hooks
    rev: v4.1.0
    hooks:
      - id: trailing-whitespace
      - id: end-of-file-fixer
  - repo: https://github.com/psf/black
    rev: 22.1.0
    hooks:
      - id: black
        language_version: python3
        args: [--quiet]
```

---

### Usage

1. Setup once: `pre-commit install`
2. Now `pre-commit` will run automatically on `git commit`

---

### Optional Usage

Manually run `pre-commit`

* All files: `pre-commit run --all-files`
* Selected files: `pre-commit run --files <list of files>`
* Selected hooks: `pre-commit run black`

---

### Output

```shell
pre-commit run --all-files
[INFO] Initializing environment for https://github.com/pre-commit/pre-commit-hooks.
[INFO] Initializing environment for https://github.com/psf/black.
[INFO] Installing environment for https://github.com/pre-commit/pre-commit-hooks.
[INFO] Once installed this environment will be reused.
[INFO] This may take a few minutes...
[INFO] Installing environment for https://github.com/psf/black.
[INFO] Once installed this environment will be reused.
[INFO] This may take a few minutes...
Check Yaml...............................................................Passed
Fix End of Files.........................................................Passed
Trim Trailing Whitespace.................................................Failed
- hook id: trailing-whitespace
- exit code: 1

Files were modified by this hook. Additional output:

Fixing sample.py

black....................................................................Passed
```

---

## Summary

![](https://miro.medium.com/max/1016/1*SE_FC8cspNAz_pFojUEsTg.jpeg)
