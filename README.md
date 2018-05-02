![BookLeaf logo](img/logo.png "BookLeaf logo")

# BookLeaf

BookLeaf is a 2D unstructured hydrodynamics mini-app.

There are two primary implementations of BookLeaf, one in C++ and the other in
Fortran. This repository contains information applicable to both versions, and a
Git submodule referencing each.

## Installation

The C++ version of BookLeaf can be installed using [Spack](https://spack.io/).

```
spack install bookleaf-cpp
```

In order to build either the C++ or Fortran version of BookLeaf manually, first
run:

```
git submodule init && git submodule update
```

to checkout the current releases, and then refer to the README files for each
implementation for specific build instructions.

## Release history

* 02/05/2018, version 2.0
