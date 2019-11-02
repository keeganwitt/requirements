# Requirements plugin

https://plugins.jetbrains.com/plugin/10837

## Syntax

[PEP 440 -- Version Identification and Dependency Specification](https://www.python.org/dev/peps/pep-0440)

[PEP 508 -- Dependency specification for Python Software Packages](https://www.python.org/dev/peps/pep-0508)

[requirements-file-format](https://pip.pypa.io/en/stable/reference/pip_install/#requirements-file-format)

## Features

* Highlighting and Syntax check for requirements.txt files in IDE
* Reference to subrequirements files (Ctrl + click)
* Opening packages in a browser (Ctrl + click)
* Reformat file

## Code Inspections

PyCharm, and other products if the Python plugin is installed:
* Check if packages are installed
* Checking package versions

All IDEs:
* Check if there are files to which there is a link
* Check for duplicate definitions

## Quick fixes

PyCharm, and other products if the Python plugin is installed:
* Install package

## TODO

* Distinguish a plain text file from file requirements.txt
* Support all relations
* Opening local source code
* Add tests
* Code completion
