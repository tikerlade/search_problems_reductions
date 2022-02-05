[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Python checks](https://github.com/tikerlade/search_problems_reductions/actions/workflows/python_checks.yml/badge.svg)](https://github.com/tikerlade/search_problems_reductions/actions/workflows/python_checks.yml)


# Reductions of search problems
The goal of this project is to complete reductions of search problems in Python.

Search problems (NP problems) are those, whose potential solution you can validate in polynomial time.
However, you cannot find solution for this problem in polynomial time.
Some NP problems can be converted one to another in polynomial time. And this project is aimed to do this.


## Plan of supported reductions
* SAT → 3-SAT
* 3-SAT → IS (independent set problem)
* 3-SAT → X3C (exact cover by 3-sets problem)
* IS → VC (vertex cover problem)
* IS → Clique

## Problems definitions
TBD

## Technology stack :gear:
- GitHub Actions CI
- pre-commit
  - mypy
  - flake8
  - pytest
  - isort
  - check-docstrings-first
