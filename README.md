# conda-training

Conda repository with the same testing environment as [BIOCONDA repository](https://bioconda.github.io).

No upload to anaconda or quai.io repositories.

## Contributing

1. Fork the project
2. Write your recipe
3. Create a Pull Request (PR)

## Test your recipe with simulate-travis.py

### Initialisation

`./simulate-travis.py --bootstrap /tmp/miniconda --overwrite`

### Build a specific recipe

`./simulate-travis.py --git-range HEAD --disable-docker --packages mypackage`
