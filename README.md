# Python for data science

>Note this repo is a work in progress

## Jupyter notebooks covering Python & it's application to data science

### To run code:

1. Install VSCode and the VSCode Python plugin (which includes Jupyter notebooks)

2. Clone the repo with GitHub CLI:

```
gh repo clone CormacKinsella/python-data-science
```

3. Set up the Conda environment for software dependencies. [Get conda here](https://docs.conda.io/en/latest/miniconda.html#linux-installers). To create and activate the environment:

```
conda env create -f python-data-science.yml
conda activate python-data-science
```

4. Open any of the notebooks within VSCode, and explore code interactively!

### Notebooks

#### For getting familiar with Python:

*python-fundamentals.ipynb*

>Setting up environment, fundamentals of stdlib Python coding

#### Bioinformatics:

*python-bioinformatics.ipynb*

>Differences between Shell and Python pipelines, Subprocess, the Sh package, bioinformatics packages made for python, Biopython

#### Machine learning:

*python-machine-learning.ipynb*

>Machine learning with Python

#### Data science and visualisation:

*python-data_manipulation_and_graphics.ipynb*

>Numpy, Pandas, and graphics for data science

#### Dashboard visualisation:

*python-dashboards.ipynb*

>Dashboard overview, the Dash package for Python, deploying to cloud
