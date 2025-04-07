# MLFlow Project

![Python Logo](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg) 
![VS Code Logo](https://upload.wikimedia.org/wikipedia/commons/9/9b/Visual_Studio_Code_1.35_icon.svg) 
![Miniconda Logo](https://docs.conda.io/projects/conda/en/latest/_images/conda_logo.svg)  
![Pip Logo](https://upload.wikimedia.org/wikipedia/commons/1/1e/Pip_logo.svg) 
![MLFlow Logo](https://mlflow.org/images/logo.svg)  

## Overview

Welcome to the **MLFlow Project**! This project demonstrates how to set up a Python development environment and use **MLFlow** for machine learning workflows.

### Key Features:
- Environment setup with **Miniconda** and **Python 3.11**
- Integration with **MLFlow** for managing machine learning models
- Easy-to-follow installation and usage instructions

## Requirements

- **Python 3.11** or later
- **Conda** / **Miniconda** for environment management
- **Pip** for package installation
- **MLFlow** for managing machine learning models

## Installation Guide

### 1. Check Python Version

To check the Python version, run:

```bash
python --version 
```

### 2. Check Pip Version

To check the pip version, run:

```bash
pip --version
```

## If python --version is not working and python3 is working then:

### 3. Set Python to Point to Python 3

If python is not pointing to Python 3, run the following command in your terminal:

```bash
sudo ln -s $(which python3) /usr/local/bin/python
```

Then verify if it works:


```bash
pip --version
```

## If python --version working then Skip Step 3

### 4. If pip3 is working but pip is not, Create a Symbolic Link for pip

Run the following command:

```bash
sudo ln -s $(which pip3) /usr/local/bin/pip
```

Now check the pip version:

```bash
pip --version
```

## If pip --version working then Skip Step 4

### 5. Create a Conda Environment with Python 3.13.2


Run the following command to create the Conda environment for your project:

```bash
conda create --name venv python=3.13.2
```

Activate the environment using this command:

```bash
conda activate venv
```

### 6. Install Required Libraries from requirements.txt File

You can install the required dependencies for the project using Pip:

```bash
pip install -r requirements.txt
```

## Usage
Once everything is set up, you can use MLFlow to manage your machine learning workflows.

### Start the MLFlow UI

To start the MLFlow UI and monitor your experiments, use the following command:

```bash
mlflow ui
```

The UI will be available at http://localhost:5000.

## Contributing

We welcome contributions to this project! If you'd like to contribute:

1. **Fork** the repository.
2. **Clone** your fork to your local machine.
3. **Make your changes**.
4. **Submit a pull request** to the main repository.

## License

This project is licensed under the **MIT License**.

## Contact

For any issues or questions, please feel free to **open an issue** or email me at **jamil138.amin@gmail.com**.
