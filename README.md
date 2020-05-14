# IWME 502 / CIVL 598G: Advanced Engineering Hydrology

Labs and Exercises for Advanced Engineering Hydrology are provided in this code repository.  

## Getting Started with Interactive Python Notebooks

The exercises in this course will be provided in Jupyter notebooks.  These files can be accessed in the following ways:

* **in the cloud**: notebooks can be accessed here(add links to Syzygy and/or Binder) where they will be set up to run in the cloud to run in your web browser.  It's important to note that files accessed this way **will not be saved**, and any changes made will have to be saved locally to your computer, and rewritten if you exit and restart the instance.  Alternatively, you can set up open-source software to run...
* **on your computer**: It is recommended to use the package and environment manager [Anaconda](https://www.anaconda.com/).  Programming in Python is exciting and accessible because it uses powerful functions written in application-specific libraries.  Anaconda is the software that (does its best to) make sure everything cooperates and runs smoothly.  After installing Anaconda, it is recommended to install [Jupyter Lab](https://jupyter.org/).  


### Before the first class

Please ensure you have Python installed (version should be Python 3.6 or greater) and you have set up your programming environment and can create and run a Jupyter notebook.  [Detailed instructions can be found here.](https://nbviewer.jupyter.org/github/ehmatthes/intro_programming/blob/master/notebooks/programming_environment.ipynb)

A discussion thread dedicated to installation and setup will be created on Canvas.  If you still have difficulty after reviewing the resources provided here, please post questions (with as much detail as you can provide) to the Canvas discussion forum and the TA will be available to help.

### Learning Resources

* [How to run code in the notebook](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Running%20Code.ipynb).  Basics of Python syntax and programming in the Jupyter notebook.
* [Matplotlib](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb) is a popular library for creating a wide variety of plots.  
* [Introduction to Python](https://nbviewer.jupyter.org/github/ehmatthes/intro_programming/blob/master/notebooks/index.ipynb).  An introductory course taught through an interactive Python notebook in Jupyter.

A comprehensive list of interesting, useful, and informative Jupyter notebook examples can be found [here](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks).

## Other Information

### Package Installation

If when running a code cell in Jupyter you encounter the following type of error:

![Example Package Error](img/package_error.png)

This generally means a package has not been installed.  In this case, the package is `Pandas`, which can be installed by creating a new cell:

![new cell](img/new_cell.png)

Typing the following (you can replace `pandas` with the name of the package you need to install)

![](img/package_install.png)

And executing the cell (shift + enter), or the 'run' button.