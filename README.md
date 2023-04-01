# transformations

Homogeneous Transformation Matrices and Quaternions by Christoph Gohlke
<http://www.lfd.uci.edu/~gohlke/>

The code is all original as per the original author.  I have only packaged it
for installation convenience.  The license terms remain as the author defined
them and are described in full at the top of the transformations.py file and in
a separate LICENSE file included in this distribution.

## Building

Make sure the build package is installed:

```bash
pip install --upgrade build
```

Build the transformations package

```bash
python -m build
```

## Installation

The build module will create a .whl file in the dist/ directory (double check
actual file name in your dist/ directory).

```bash
pip install dist/transformations_northstaruas-2013.6.29-py3-none-any.whl --user
```

## Documentation and usage

Please refer to the transformations.py file itself for available functions and usage as it is self-documenting.
