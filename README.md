# CMS NanoAOD open data in Python


[invariant_mass.ipynb](https://github.com/cms-opendata-education/cms-nanoaod-uproot/blob/main/invariant_mass.ipynb) is a minimal notebook for a quick exploration (or demonstration) of the CMS open data in the [NanoAOD format](https://opendata.cern.ch/docs/cms-getting-started-nanoaod) using Python.

It reads an input file, computes the invariant mass of the two leading muons in each collision and plots a histogram of the values. In principle, a file from any NanoAOD or NanoAODSIM dataset will do, as long as they contain events with two muons.

It is very simple on purpose, and is not to be taken as a programming example.

[invariant_mass.py](https://github.com/cms-opendata-education/cms-nanoaod-uproot/blob/main/invariant_mass.py) is an equivalent in plain Python.

[requirements.txt](https://github.com/cms-opendata-education/cms-nanoaod-uproot/blob/main/requirements.txt) contains the Python packages needed for execution.

## Launch the notebook

Launch the notebook on a browser window:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-nanoaod-uproot/HEAD?urlpath=%2Fdoc%2Ftree%2Finvariant_mass.ipynb)

## Run locally

If you prefer running locally, get the code with

```
git clone https://github.com/cms-opendata-education/cms-nanoaod-uproot.git
cd cms-nanoaod-uproot
```

Optionally, create a virtual environment in order not to interfere with your usual working environment:

```
python3 -m venv venv
source venv/bin/activate
```

Install the Python packages needed for the code to run, and jupyterlab for running the notebook:

```
pip install -r requirements.txt
pip install jupyterlab
```

Start the notebook with

```
jypyter-lab
```

It opens in your default browser in http://localhost:8888/lab

