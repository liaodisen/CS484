# Environment Setup

This project requires a Conda environment with the latest compatible versions of NumPy and Numba.

## Prerequisites

* **Anaconda** or **Miniconda** must be installed on your system.
    * [Download Miniconda](https://docs.conda.io/en/latest/miniconda.html) (Lightweight, recommended)
    * [Download Anaconda](https://www.anaconda.com/products/distribution) (Full suite)

## Quick Start

### 1. Create the Environment
Run the following command in your terminal. This creates an environment named `numpy_tutorial` and installs the latest versions of NumPy and Numba from the conda-forge channel.

```bash
conda create --name numpy_tutoral -c conda-forge numpy numba