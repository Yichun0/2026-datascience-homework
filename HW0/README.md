# Homework 0
**Introduction to Data Science - MATH 4100 / COMP 5360.** 
*There is nothing to turn in for this homework BUT if you do not complete this
by the end of the first week of class, you will not be prepared going
forward.* 


Welcome to MATH 4100 and Computing 5360 – Introduction to Data Science. In this class, we will be using a variety of tools that will require some initial configuration. To ensure everything goes smoothly moving forward, we will set up the majority of those tools in this homework. This homework will not be graded, but **it is highly recommended that you complete it before the second lecture** and **essential by the second week** as it sets up the tools that we will be using in class for exercises.

## 1. Setup

We'll often work on practical skills related to data science. That means we'll write code, and we'll do that in a programming language called Python.

Python has three advantages for this class: it's pretty easy to learn, it's the language of choice for many data scientists, and it can be used inside of Jupyter Notebooks – more on the latter will follow later.

We also assume that you know the basics of how to work with a terminal / console. If you don't check out an introduction like [this](http://tutorial.djangogirls.org/en/intro_to_command_line/).  

First, we'll need to install some things:

### 1.1 Installing Python (& Anaconda)

Chances are, if you're on a mac, you already have Python installed. You can simply try to run python from a console by running

```
$ python
```

However, as most software, Python comes in different versions and is packaged differently depending on your needs. In this class we'll use a Python distribution called Anaconda. Anaconda comes with a lot of packages that we'll need, so it is the most hassle-free option for us.

Go to [this website](https://www.anaconda.com/download/) and install anaconda for Python 3.13.9 for your operating system. [Here](https://docs.continuum.io/anaconda/install) are installation instructions if you need them. If you already have anaconda installed, please make sure that you're using the latest version or [update](http://docs.continuum.io/anaconda/install/update-version/) if necessary. Note that 3.13.9 is what comes with the latest anaconda version (2025.12-1).

*Note for students with an Intel-based Mac*: anaconda stopped creating build
packages for these in August 2025. We recommend installing the anaconda
version prior (2025.06-1) which has a slightly older version of Python
(3.13.5). Note this version is only available via the [archive](https://repo.anaconda.com/archive/). You will likely want the version: Anaconda3-2025.06-1-MacOSX-x86_64.pkg


Anaconda is both, a package manager and an environment manager. A package manager manages, well, packages. Packages add specific pieces of functionality - there are packages for web scraping, or for data visualization, for example. An environment manager, in contrast, allows you to have different versions of packages installed at the same time. We'll dive into environments and packages when we need them at a later point.


*If you are familiar with maintaining development environments* you **may**
install Pyhton 3.13.9 and all the packages we use in this class separately.
However, instructional support in office hours for this route will be limited.


### 1.2 Check Your Python Version

From Anaconda Navigation,  go to the "Environments" tab on the left-hand side of
Anaconda Navigator. From there, you can search for python (or any of the other
packages installed) and the version will be clearly indicated. You can use the
search on the far right or you can scroll down to "python" to check the
version number.

You can also check out the [official website](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html) for more details on anaconda, environments, and packages.


### 1.3 Test Jupyter Notebooks

***Check out the official Jupyter Notebooks documentation [here](http://jupyter.readthedocs.io/en/latest/index.html) for all the details***

We'll be running Python through Jupyter Notebooks as they are great for the data science process and for teaching, but you should be aware of the other options we discuss here.

Notebooks are stored in files that end with a `.ipynb` extension. They are included in the [basic-python](https://github.com/datascience-course/2026-datascience-homework/tree/main/HW0/basic-python) folder in this directory. Download them and save them to a folder.

Notebooks make use of an improved, interactive client for python called [IPython](https://ipython.org/). IPython might already be installed in the latest version if you did a clean anaconda install. To check, we'll use anaconda to install the proper version of IPython. Run:

From Anaconda Navigator's Home window, scroll to the "Jupyter Notebook" card.
Note it may be right next to the "JupyterLab" card. We'll just use the base
Jupyter Notebook, so click "Launch" on that.

This will start the notebook server and should open up a browser window point to [http://localhost:8888/](http://localhost:8888/) that will look like that:

![Jupyter Notebook Screenshot](jupyter.png)

Note this gives you a file browser. You will need to navigate to where you
downloaded HW0 to see the available notebooks. Click on the
`02-notebooks.ipynb` entry to see if it works. We'll take it from there in the
labs!

### 2. Self Study: Python

You can augment lecture by going through [Google's Python Tutorial](https://developers.google.com/edu/python), sections Intro, Strings, Lists, Sorting, Dicts and Files. 
