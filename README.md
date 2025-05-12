# README.md 

This is the README for the PhD course in Deep Learning for **Data Driven Life
Science**.

## Installing Jupyter + Packages

Below we will walk you through installing **Miniconda**, creating a Conda environment, and installing essential Python tools for deep learning.

### Miniconda

1. Go to: https://www.anaconda.com/download/success
2. Download the **Miniconda installer** for your OS and architecture.
3. Run the installer and follow the prompts.
4. After installation, restart your terminal or open a new one.

To verify installation:
```bash
conda --version
```

### Conda environment 

Create the conda environment using:
```bash
conda create -n dl python=3.10
```

and activate the envrionment using:

```bash
conda activate dl
```

Finally, install the relevant packages using:

```bash
conda install -c conda-forge tensorflow jupyterlab numpy pandas matplotlib
```

###  Jupyter Lab

To start jupyter run the following command:
```bash
jupyter lab
```

**REMEMBER** to activate the conda environment before running jupyter lab.



