# transformations

Homogeneous Transformation Matrices and Quaternions by Christoph Gohlke <http://www.lfd.uci.edu/~gohlke/>

## Building

Make sure the build package is installed:
```
pip install --upgrade build
```

Build the transformations package
```
python -m build
```

## Installation

The build module will create a .whl file in the dist/ directory (double check actual file name in your dist/ directory).
```
pip install dist/transformations-2013.6.29-py3-none-any.whl
```