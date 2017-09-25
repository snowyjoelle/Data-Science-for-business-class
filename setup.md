# MGT-432: Data Science for Business | SETUP

We **strongly** recommended you use a Mac OS X or Linux computer for this class. You can then use UNIX commands from a terminal. It is, however, possible to install everything you need on a Windows computer, but we don't support the Windows environment.

#### GIT
We will collaborate through a code versioning and hosting solution known as `git`.
There are several services that host git "repositories" - namely Github.com and BitBucket.com. We will use Github.com - it is free, at least for when you participate in this course.

1. Open an account on [Github.com](Github.com)  
2. Install `git` on your computer - see GitHub.com for download and install instructions.
3. Learn basic git commands - see [overview](http://rogerdudler.github.io/git-guide/)
4. Learn how **`git`** works - see [overview](https://git-scm.com/)

#### Anaconda distribution of Python
Continuum Analytics provides a free distribution of Python that is pre-configured for scientific computing - this is called "**Anaconda**." Python comes in two versions (version 2.x and 3.x) - everything in this course will run on Version 3.x.

1. Visit https://www.continuum.io/downloads
2. Install the Python **3.x** version (3.6 is latest version right now)

#### Jupyter Notebook

*Jupyter Notebook* will be the primary development environment and code editor for the course, and is now widely used in Data Science and scientific computing projects. Jupyter is a "read–eval–print loop" (**REPL**) system that allows you to work interactively with your code. All of the code examples and demos in class will be in a *Jupyter Notebook*. You MUST submit your Assignments and Final Project as a *Jupyter Notebook*.

*Jupyter* is installed onto your computer automatically by Anaconda, but then executes locally in a web browser. You can start the Jupyter Notebook **Server** as follows:  

1. In a terminal session, go to a working directory and start the server by executing: `jupyter notebook`.
2. From there you can create a new notebook and start coding.

#### Python libraries

Anaconda installs all of the commonly used Python libraries for data science by default. If a library is not installed, however, or a version update is needed, then we will inform you and you will need to install it manually by using a installer program, as follows:

1. using `conda install lib_name` from terminal session, or equivalently through anaconda navigator GUI using Environments tab
2. if conda does not work, then `pip install lib_name` from a terminal session). Avoid install a library using pip if you can install it using conda to prevent inconsistencies.

#### Python IDE

You may want to use a more advanced "IDE" for your programming - especially if you already have coding experience. An IDE is software that provides an "Integrated Development Environment" for managing your code, and in particular will provide deeper contextual prompts when working with big code bases.
Anaconda by default installs the **Spyder** IDE which you can open through Anaconda navigator.

Another popular Python IDE is the **PyCharm** from jetbrains. To install, do the followings:     

  * Install PyCharm from [JetBrains](https://www.jetbrains.com/pycharm/)  
  * Request a [free license](https://www.jetbrains.com/student/) for the Pro version.

IMPORTANT: For this course, you MUST do your assignments and project in a Jupyter notebook. Using an IDE is optional and best suited for advanced programs; we do not support or troubleshoot the use of other IDEs.
