# Quadratic Equations Solver

Pre-commit hook which run tests for Quadratic Equations Solver

## Usage

First of all, make sure that shebang line in **tests.py** is pointing to your python interpreter.

### Linux & Mac OS X
Specify python executable. You can find it with 

`$ which python`

### Windows
You might want to remove shebang line from test.py and change **pre-commit** file to something like this:

```
#!/bin/sh
python tests.py
```

### General

Place **pre-commit** file in `.git/hooks/`. From now on each `git commit` will run tests from **tests.py**. Commit is prevented if any of the tests fails.

## Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
