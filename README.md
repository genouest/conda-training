# conda-training

Conda repository with the same testing environment as [BIOCONDA repository](https://bioconda.github.io).

# use simulate-travis.py

## initialisation

`./simulate-travis.py --bootstrap /tmp/miniconda --overwrite`

## build a specific recipe

`./simulate-travis.py --git-range HEAD --disable-docker --packages mypackage`
