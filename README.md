# Python for data science

>Note this repo is a work in progress

## Jupyter notebooks covering several topics in Python basics, data science, and bioinformatics

### To run:

1. Install VSCode and the VSCode Python plugin, the latter allows work with Jupyter notebooks

2. Clone the repo with GitHub CLI:

```
gh repo clone CormacKinsella/python-data-science
```

3. Set up the Conda environment for software dependencies. [Get conda here](https://docs.conda.io/en/latest/miniconda.html#linux-installers). To create, activate, and check the environment:

```
conda env create -f python-data-science.yml
conda activate python-data-science
conda list
```

4. Open any of the notebooks within VSCode, and explore code interactively!

### Notebooks

For getting familiar with Python:

>python-fundamentals.ipynb
>>This includes setting up Conda, VSCode/Jupyter, Git, and fundamentals of stdlib Python

Bioinformatics:

>python-bioinformatics.ipynb
>>Covering differences between Shell and Python pipelines, Subprocess, the Sh package, bioinformatics packages made for python, Biopython

Machine learning:

>python-machine-learning.ipynb
>>Basics of machine learning with Python

Data science and visualisation:

>python-data_manipulation_and_graphics.ipynb
>>Numpy, Pandas, and graphics for data science

Dashboard visualisation:

>python-dashboards.ipynb
>>What are dashboards and when are they used, what are APIs, which dashboard software is out there, the Dash package, API integration
