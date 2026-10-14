# Claveles Notebooks

`claveles-notebooks` is a collection of example Jupyter Notebooks demonstrating quantum circuit construction, simulating computing quantum circuits, and execution using [Claveles](https://github.com/OptQC-Corp/claveles), the Python SDK for continuous-variable quantum computing.

## Overview

This repository serves as a hub for interactive tutorials, guides, and practical code examples for continuous-variable optical quantum computing with Claveles.

## Repository Structure

```text
claveles-notebooks/
├── LICENSE
├── README.md
├── pyproject.toml
└── notebooks/
    └── *.ipynb  # Example and tutorial notebooks
```

## Getting Started

To run the notebooks locally, ensure you have a Python 3.10+ environment set up with `claveles` and `jupyter` installed:

```sh
# Clone this repository
git clone https://github.com/OptQC-Corp/claveles-notebooks.git
cd claveles-notebooks

# Install Claveles SDK and Jupyter Lab
pip install claveles jupyterlab

# Launch Jupyter Lab
jupyter lab notebooks/
```

## License

This repository is released under the **Apache License, Version 2.0**. See the [LICENSE](LICENSE) file for more details.
