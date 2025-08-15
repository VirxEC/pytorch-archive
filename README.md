# Shared cpu-only PyTorch install archive

The archive produced is able to be loaded at runtime by Python, allowing self-contained Python exes to share PyTorch files.

Python 3.12 only, targets Windows & Linux.

Packages included in the redistributable include PyTorch's dependencies downloaded from pip _except for numpy_, which are:

1. filelock
1. fsspec
1. jinja
1. markupsafe
1. mpmath
1. networkx
1. sympy
1. torch
1. torchgen
1. typing_extensions
