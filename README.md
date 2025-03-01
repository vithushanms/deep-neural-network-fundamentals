# deep-neural-network-fundementals

A repository of notebooks which has the collection of notebooks that explains fundamentals of deep-neural-networks along with many useful notes and code examples.

# Env setup

There are two opeions to setup the environment for running the notebooks.

1. Using online colab notebooks (https://colab.google)

2. Using local jupyter notebooks. follow the below steps to setup the environment using miniconda.

## Setup the environment using miniconda

1. Install miniconda from the below link
   https://docs.conda.io/en/latest/miniconda.html

2. Create environment using the below command

```bash
conda env create -f environment.yml
```

3. Activate the environment using the below command

```bash
conda activate dnn-fundementals
```

4. (Optional) if you don't have poetry already, install poetry using the below command

```bash
pip install poetry
```

5. Install the dependencies using the below command

```bash
poetry install
```

6. If you don't have graphiz installed, install it using the below command

on mac

```bash
brew install graphviz
```

on ubuntu

```bash
sudo apt-get install graphviz
```

# Materials

01. `back-propagation-fundamentals`: A collection of notebooks that explains the fundamentals of back propagation.