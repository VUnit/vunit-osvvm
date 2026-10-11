# vunit-osvvm

A VUnit package providing the OSVVM library.

## Overview

For information about OSVVM, see https://github.com/OSVVM/OSVVM/blob/master/README.md

## Installation

```bash
pip install vunit-osvvm
```

## Adding vunit-osvvm to a VUnit Project

The `vunit-osvvm` package is added to a VUnit project by calling the `add_package` method from the VUnit
run script. See example below.

```python
from vunit import VUnit

vu = VUnit.from_argv()
vu.add_vhdl_builtins()

# Add vunit-osvvm
vu.add_package("vunit-osvvm")
```
