# How to run these notebooks

This website is currently hosted as a set of static webpages on GitHub and does not yet feature any of the interactive features available in Jupyter Book 2.0 / MyST Markdown Document Engine. 

## To run a notebook using (JupyterLab)[https://jupyterlab.readthedocs.io/en/latest/getting_started/overview.html] 
1. download the Jupyter notebook by clicking the download icon at the top right of the center column of page (just above the page title). 
2. launch JupyterLab on your own computer or a JupyterHub server
3. upload and launch the notebook in the usual way

## To convert a Jupyter Notebook to a (Marimo)[https://marimo.io] notebook: 

Note: this requires you to be able to open and use the terminal app on your computer

1. install marimo using uv (so you can build stand-alone 'sandboxed' notebooks)
2. convert your .ipynb Jupyter notebook using the following command

```uv run marimo convert your_notebook.ipynb -0 your_notebook.py'''

More details here: 
[Coming from Jupyter](https://docs.marimo.io/guides/coming_from/jupyter/)
