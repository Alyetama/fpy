# fpy

Uses yapf to format python files, but with properly sorted import statemnts.

## Requirements

- [Python>=3.6](https://www.python.org/downloads/)

## Installation

```
pip install fpy
```

## Usage

```
usage: fpy [-h] [-s {pep8,google,yapf,facebook}] [-i] [-o] [-n]
           files [files ...]

positional arguments:
  files                 files to format

optional arguments:
  -h, --help            show this help message and exit
  -s {pep8,google,yapf,facebook}, --style {pep8,google,yapf,facebook}
                        Formatting style
  -i, --in-place        Make changes in-place
  -o, --only-imports    Only return sorted import statements
  -n, --show-line-numbers
                        Render a column for line numbers
```

## Exampls

[![asciicast](https://asciinema.org/a/gsPwjiEGMzQZkDjF4eExzwpm2.svg)](https://asciinema.org/a/gsPwjiEGMzQZkDjF4eExzwpm2)
