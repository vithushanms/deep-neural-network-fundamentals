# deep-neural-network-fundementals

A repository of notebooks which has the collection of notebooks that explains fundamentals of deep-neural-networks.

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
