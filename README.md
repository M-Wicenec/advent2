# advent2

[![codecov](https://codecov.io/gh/M-Wicenec/advent2/branch/main/graph/badge.svg?token=advent2_token_here)](https://codecov.io/gh/M-Wicenec/advent2)
[![CI](https://github.com/M-Wicenec/advent2/actions/workflows/main.yml/badge.svg)](https://github.com/M-Wicenec/advent2/actions/workflows/main.yml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)


Awesome advent2 created by M-Wicenec

## Installation

There are multiple options for the installation, depending on how you are intending to run the DALiuGE engine, directly in a virtual environment (host) or inside a docker container. You can also install it either from PyPI (latest released version).

## Install it from PyPI

### Engine in virtual environment
```bash
pip install advent2
```
This will only work after releasing the project to PyPi.
### Engine in Docker container
```bash
docker exec -t daliuge-engine bash -c 'pip install --prefix=$DLG_ROOT/code advent2'
```
## Usage
For example the MyComponent component will be available to the engine when you specify 
```
advent2.apps.MyAppDROP
```
in the AppClass field of a Python Branch component. The EAGLE palette associated with these components are also generated and can be loaded directly into EAGLE. In that case all the fields are correctly populated for the respective components.

