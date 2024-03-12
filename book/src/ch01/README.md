# Chapter 01 - Introduction, Tools, and Formatting

## Documentation
### Code comments
### Docstrings
### Annotations
## Tools
### Checking type consistency
#### mypy
https://github.com/python/mypy
```bash
$ pip install mypy
```
* checkout
```bash
mypy --strict src/type_hinting_example.py.py
mypy --strict src/type_hinting_example_2.py.py
```
#### pytype
https://github.com/google/pytype
```bash
$ pip install pytype
```
### Generic validations in code
#### pylint
```bash
$ pip install pylint
```
#### Coala
https://github.com/coala/coala

### Automatic formatting
#### black
* https://github.com/psf/black

#### yapf
* https://github.com/google/yapf

### Setup for automatic checks
see [Makefile](./Makefile)