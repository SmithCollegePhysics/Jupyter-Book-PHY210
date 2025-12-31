# uv and marimo installation

hese instructions are from (Marimo/Getting Started)[https://docs.marimo.io/getting_started/installation/]


According to Marimo: uv is a next-generation Python package installer and manager that is 10-100x faster than pip, and also makes it easy to install Python and manage projects. Create a uv project with uv init; this creates and manages a virtual environment for you behind-the-scenes. For detailed information on using marimo with uv, see our (uv guide)[https://docs.marimo.io/guides/package_management/using_uv/].

## install uv (from Real Python https://realpython.com/python-uv/)

### terminal command to install uv for Linux and macOS 
```$ curl -LsSf https://astral.sh/uv/install.sh | sh```

### verify version and check for updates 
```uv --version
   uv self update```
   
## install marimo in a safe virtual environment using uv
   
### create a virtual environment

### step 1: make a directory for your project 
create a new directory in the usual way where you want the python files to exist

### step 2: terminal navigation
use the terminal to navigate to that newly created directory
1. type `pwd' to print the current directory seen by the terminal app
2. type 'ls' to list subdirectories
3. type 'cd your_preferred_subdirectory' to change current directory to that subdirectory
4. repeat `pwd` and `ls` as needed for confirmation
5. type 'cd .. ' if you want to go up to a higher level directory

### step 3: terminal commands

1. create a uv project by typing  `uv init` (once in the proper directory)
2. install marimo by typing 'uv add marimo' or 'uv add marimo[recommended]' (see below)
3. check that everything worked by typing 'uv run marimo tutorial intro' 

From the installation instructions: 
```
marimo is lightweight, with few dependencies, to maximize compatibility with your own environments. To unlock additional features in the marimo editor, including SQL cells, AI completion, server-side plotting of dataframe columns, and more, we suggest installing marimo[recommended]
```







	




