# 9th Patatrack Hackathon

## Required Packages
The notebook requires two python packages: `uproot` and `numpy`.

You can install them in different ways based on your environment.

## Getting Started on your Machine

### PIP

```
pip install numpy notebook uproot
```

### Anaconda

```
conda config --add channels conda-forge
conda update --all

conda install numpy
conda install notebook
conda install uproot
```

### Anaconda using the provided environment files
Another option is to use the [`environment.yml` file](environment.yml) provided by us.

Download the file describing the environment (you can dowload the file manually as well):
```
wget https://patatrack.web.cern.ch/patatrack/wiki/environment.yml
```

Create the environment:

```
conda env create -f environment.yml
```

Activate the environment:

```
conda activate cern-hackaton
```

You can execute jupyter using `jupyter notebook`

## Create a Python Virtual Environment on LXPlus

Login to the machine:
```
ssh [your_cern_username]@lxplus.cern.ch
```

Create the environment and install the needed packages:
```
python3 -m venv ./venv
source venv/bin/activate
pip install numpy notebook uproot
```

## Clone the base repository

```
git clone https://github.com/cms-patatrack/tue-hackathon-2021.git
```

## Run the `hackaton_demo` notebook
You can open the `hackaton_demo` notebook using jupyter
```
jupyter notebook [location]/hackathon_demo.ipynb
```
