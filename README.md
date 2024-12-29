# Setting Up a Conda Environment and Installing Libraries

This guide walks you through creating a Conda environment and installing essential libraries for Python development, including Pygame, PyTorch, and Matplotlib.

## 1. Download and Install Anaconda
Before setting up the Conda environment, ensure you have Anaconda installed on your system. You can download it from the official [Anaconda website](https://www.anaconda.com/products/distribution) and follow the installation instructions for your operating system.

## 2. Create a New Conda Environment
To create a new Conda environment named `pygam_env` with a specified Python version:

```bash
conda create -n pygam_env python=<desired_version>
```

## 3. Activate the Conda Environment
Once the environment is created, activate it using the following command:

```bash
conda activate pygam_env
```

## 4. Install Pygame Library
Pygame is a collection of Python modules used for creating video games. It provides tools for handling graphics, sound, and input. Install it by running:

```bash
pip install pygame
```

## 5. Install PyTorch Libraries
PyTorch is a popular open-source machine learning library. Install PyTorch and its associated libraries (`torch` and `torchvision`) with the following command:

```bash
pip3 install torch torchvision
```

## 6. Install Matplotlib Library
Matplotlib is a Python plotting library for creating static, interactive, and animated visualizations. To install Matplotlib along with IPython for interactive work:

```bash
pip install matplotlib ipython
```

---
