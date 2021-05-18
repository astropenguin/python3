# python3
Global Python 3 environment managed by [Poetry]

This repository manages Python packages to be used in a global Python 3 environment.
With a local [Poetry] setting, it does not make a virtual environment, so the packages will be directly installed in the global site-packages directory.

## Usage

1. Make sure that the target `python3` is first in your PATH.
1. Make sure that [Poetry] is installed.
1. Clone this repository, `cd` to it, and run `poetry install`.

```shell
$ git clone https://github.com/astropenguin/python3
$ cd python3
$ poetry install
```

## Tips

If you use [Homebrew], you can choose a Python version to use.

```shell
$ brew install python@3.8
$ brew link python@3.8
```

[Homebrew]: https:brew.sh
[Poetry]: https://python-poetry.org
