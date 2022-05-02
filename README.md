# Spring 2022 CS170 Project Skeleton

## Requirements

A Python skeleton is available in the `python` subdirectory. The Python
skeleton was developed using Python 3.9, but it should work with Python
versions 3.6+.

## Usage

### Solving

To output the penalty of a specific input, use the solver skeleton at 
[`python/solve.py`](python/solve.py).
```bash
python3 solve.py case.in --solver=naive case.out
```

To generate an output file, we will use
[`python/solve_all.py`](python/solve_all.py).
Run

```
python3 python/solve_all.py inputs outputs
```

in the root directory. "outputs" will be the name of a new folder chosen by you.
