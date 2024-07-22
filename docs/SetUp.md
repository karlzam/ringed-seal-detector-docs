# Set Up

## Overview 

This tutorial uses Python version 3.9.17 and Ketos version 2.7.0.

## Installation Steps 

1. Install [Anaconda](https://docs.anaconda.com/anaconda/install/windows/) or [Miniconda](https://docs.anaconda.com/miniconda/). Miniconda is a great alternative for users who don't normally use Python, as it installs the minimum amount of packages necessary.
2. Open the Anaconda Prompt
3. Create a Python environment (called RS_env in this example) using the command: 

```commandline
conda create -n RS_env python=3.9.17
```

4. Activate your environment: 

```commandline
conda activate RS_env
```

5. Install ketos version 2.7.0: 

```commandline
pip install ketos=2.7.0
```

This may take a few minutes. Note the below error message if you run into issues with Numpy versioning.

!!! note

    ⚠️ **If you are already a Python user**: Some users experienced issues with NumPy versioning. If you have errors (example: loading NDarray), force install NumPy version 1.24.4 in your detector environment.
    
    Type (with your environment activated): pip install numpy==1.24.4