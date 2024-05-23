# Regressions tests for the metatensor-plumed interface

[![Tests](https://github.com/lab-cosmo/plumed-metatensor-tests/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/lab-cosmo/plumed-metatensor-tests/actions/workflows/tests.yml)

This repository contains regressions tests for the interface between [metatensor
atomistic models](https://docs.metatensor.org/latest/atomistic/index.html) and
[PLUMED](https://www.plumed.org/). This interface enables using machine learning
models as collective variables in PLUMED.

The code itself lives in the [plumed repository], here you'll find tests that
check that this interface works as intended. These tests run automatically once
a week, to make sure the code keep working as intended.

You can run the tests yourself to check that you managed to compile the code by
cloning this repository and running `make` with `plumed` in your `$PATH`. Some
of the tests also require a working Python installation including
[rascaline-torch](https://github.com/Luthaf/rascaline/).

[plumed repository]: https://github.com/lab-cosmo/plumed2/tree/action-metatensor/src/metatensor
