# uv and marimo installation

These instructions are abridged from [Marimo/Getting Started](https://docs.marimo.io/getting_started/installation/)

1. uv is a superfast Python package installer and managerthat makes it easy create safe virtual environments and installing python packages into those environments. You can think of it as an alternative/ replacement for  conda/miniconda. 
2. Marimo is a new alternative to JupyterLab notebooks you may be interested in trying. 
3. Installing Marimo using uv also allows [sandboxing](https://docs.marimo.io/guides/package_management/notebooks_in_projects/?h=sandboxing): creating standalone self-contained reproducible notebooks that load all the python packages for you (and know which ones to use)

IMHO, the reproducibility that comes with sandboxing is one of the best reasons to try out Marimo as a computational/lab notebook. For detailed information on using marimo with uv, see [uv guide[](https://docs.marimo.io/guides/package_management/using_uv/).

## install uv [from Real Python](https://realpython.com/python-uv/)

### terminal command to install uv for Linux and macOS 
```$ curl -LsSf https://astral.sh/uv/install.sh | sh```

### verify version and check for updates 
```uv --version
   uv self update```
   
## install marimo using uv
   
### create a virtual environment

### step 1: make a directory for your project 
create a new directory in the usual way where you want the python files to exist

### step 2: terminal navigation (for Mac OS and Linux)
use the terminal to navigate to that newly created directory
1. type `pwd` to print the current directory seen by the terminal app
2. type `ls` to list subdirectories
3. type `cd your_preferred_subdirectory` to change current directory to that subdirectory
4. repeat `pwd` and `ls` as needed for confirmation
5. type `cd ..`  if you want to go up to a higher level directory

### step 3: terminal commands

1. create a uv project by typing  `uv init` (once in the proper directory)
2. install marimo by typing `uv add marimo` or `uv add marimo[recommended]` (see below)
3. check that everything worked by typing 'uv run marimo tutorial intro' 

About recommended packages (these can always be added later if preferred)
```
marimo is lightweight, with few dependencies, to maximize compatibility with your own environments. To unlock additional features in the marimo editor, including SQL cells, AI completion, server-side plotting of dataframe columns, and more, we suggest installing marimo[recommended]
```







	




