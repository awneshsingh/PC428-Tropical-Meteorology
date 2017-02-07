# Python for PC428: Tropical Meteorology

[Pacific Centre for Environment and Sustainable Development (PaCE-SD)](http://pace.usp.ac.fj/),

[The University of the South Pacific](http://www.usp.ac.fj), Suva, Fiji

Contact: [Dr. Awnesh Singh](mailto:awnesh.singh@usp.ac.fj)


## Table of Contents

- [The Anaconda Python Distribution](#the-anaconda-python-distribution)
- [Installation of Additional Libraries](#installation-of-additional-libraries)
- [Running the Jupyter Notebooks](#running-the-jupyter-notebooks)


## The Anaconda Python Distribution

You will first need to to install the **Anaconda Python distribution**. It is a completely free enterprise-ready Python distribution for large-scale data processing, predictive analytics, and scientific computing. It includes the python interpreter itself, the python standard library as well as a set of packages exposing data structures and methods for data manipulation and scientific computing and visualization. In particular it provides [Numpy](http://www.numpy.org/), [Scipy](http://www.scipy.org/), [Pandas](http://pandas.pydata.org/), [Matplotlib](http://matplotlib.org/), [scikit-learn](http://scikit-learn.org/stable/), etc., i.e., all the main packages we will be using during the semester. The full list of packages is available at:

[http://docs.continuum.io/anaconda/pkgs.html](http://docs.continuum.io/anaconda/pkgs.html)

The Anaconda Python distribution (**NOTE**: select the version shipping with Python 3.6) should be downloaded for your platform (either 32-bit or 64-bit operating system) from:

[http://continuum.io/downloads](http://continuum.io/downloads)

Execute the downloaded file and follow the instructions to install Anaconda. Once installed, you can update to the latest compatible versions of all the pre-installed packages by running the Anaconda Prompt as an Administrator [Start>Anaconda3(64-bit) then right click on Anaconda prompt to Run as Administrator]. Type the following at the terminal to update to the latest version of all pre-installed packages (the dollar represents the prompt):

```
$ conda update conda
```

Then type the following:

```
$ conda update anaconda
```

You also might want to install [pip](https://github.com/pypa/pip) to install packages from the [Python Package Index](http://pypi.python.org/pypi) by typing:

```
$ conda install pip
```

## Installation of Additional Libraries

### netcdf4

[netcdf4](https://github.com/Unidata/netcdf4-python) allows you to read and write netcdf files (version 3 and 4 supported), install it by typing:

```
$ conda install netcdf4
```

### Basemap

**Basemap** is a graphic library for plotting (static, publication quality) geographical maps (see [http://matplotlib.org/basemap/](http://matplotlib.org/basemap/)). **Basemap** is available directly in **Anaconda** using the conda package manager, install by typing:

```
$ conda install basemap
```

### Seaborn

[seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/) is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics. You should be able to install it with ```conda``` as well:

```
$ conda install seaborn
```

### xarray

[xarray](https://github.com/xarray/xarray) is a library aimed at bringing the power of Pandas to multidimensional labelled arrays, such as the ones usually associated with geophysical quantities varying along time and space dimensions (e.g., [time, latitudes, longitudes], [time, level, latitudes, longitudes], etc.) and supports reading and writing netcdf files. It can be installed via `conda` by typing:

```
$ conda install xarray
```

### And just to be sure ...

that you have all the necessary packages, type:

```
$ conda update --all
```

## Running the Jupyter Notebooks

The material for the course is in the form of [Jupyter notebooks](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html). In a nutshell, a Jupyter notebook is a web-based interactive computational environment (i.e., running in the browser) where you can combine Python code execution, text, mathematics, plots and rich media into a single document, which makes it an ideal medium for teaching and exploring code. Create a folder on your Desktop and name PC428_Python. Then on you terminal, navigate to this folder (e.g., type cd \Users\singh_aw\desktop\PC428_Python\ and press enter) then type:

```
$ jupyter notebook
```

That should bring up the Jupyter notebook dashboard (looking as below), you should be ready to go !

![](http://nbviewer.ipython.org/github/nicolasfauchereau/Python-for-data-analysis-and-visualisation/blob/master/session_1/notebooks/images/ipython_dashboard.png)

Note that what you see above and what you would see on your screen would be differernt. I shall be giving you notes and exercises to do on Python. These will be provided on Moodle and you will need to download and save them in the **PC428_Python** folder you created on your Desktop.

