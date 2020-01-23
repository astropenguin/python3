# python3
:penguin: Default Python 3 environment managed by [Poetry]

## Installation

Before installation, you need to install [Poetry] to an appropriate python:

```shell
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
```

Then run the following commands to install Python packages managed by [Poetry]:

```shell
$ git clone https://github.com/astropenguin/python3.git
$ cd python3
$ poetry install
```

## Usage

To run Jupyter Lab, for example, run the following commands:

```shell
$ cd python3
$ poetry run jupyter lab
```

For you use fish shell, the following commands will install wrapper functions of `python`, `ipython`, and `jupyter` so that you can run them without `cd` to the repository directory:

```shell
$ cd python3
$ ./configure
```

Then you can simply run Jupyter Lab anywhere:

```shell
$ jupyter lab
```

## Add packages

Follow [the Poetry's documentation].

```shell
$ cd python3
$ poetry add <package> ...
```

## Delete an environment

Follow [the Poetry's documentation].

```shell
$ cd python3
$ poetry env remove 3.7
```

<!-- references -->
[Poetry]: https://python-poetry.org
[the Poetry's documentation]: https://python-poetry.org/docs/cli
