[![Build Status](https://travis-ci.org/ajmedford/catmap.svg)](https://travis-ci.org/ajmedford/catmap)
[![Software License](https://img.shields.io/badge/license-GPLv3-brightgreen.svg?style=flat-square)](COPYING.txt)
> [!WARNING]
> This repository is no longer maintained. If you are looking for the numbers-solver implementation, please go [here](https://github.com/SUNCAT-Center/catmap).

# CatMAP

## INSTALLATION

To use the package add this directory to the PYTHONPATH, e.g. in bash
shell:

    export PYTHONPATH=$HOME/THIS_FOLDER_PATH:$PYTHONPATH

or in cshell:

    setenv PYTHONPATH $HOME/THIS_FOLDER_PATH:$PYTHONPATH

You will need to ensure that you are running python version 2.5 or
greater, and that the mpmath, numpy, scipy, ase, and matplotlib python
libraries are installed. A significant speed increase can also be
obtained by including the gmpy package.

The installation can be verified by starting python and typing the
following commands:

    import numpy
    import mpmath
    import matplotlib
    import catmap

See the [documentation](http://catmap.readthedocs.org) for more details
and tutorials.
