Scipy Native Kernels
====================

A few kernels written in cython, extracted from the SciPy code base, then ported to other acceleration engines.

To keep comparison fairs, neither parallelization nor explicit vectorization etc is used. Raw sequential portable performances.

Current engines:

- `cython <http://cython.org>`_
- `pythran <https://github.com/serge-sans-paille/pythran>`_
