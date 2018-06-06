# JupyterLab_HowTo
### Author: Teng Fu
For Chinese version, please check [关于JupyerLab的简介](README_CN.md)

This is a repository for JupyterLab related knowledge.
The aim of this repository includes:
- Introducing JupyterLab
- Tricks for JupyterLab usage


JupyterLab is a new generation of Jupyter toolkit, we can consider it as a integration and advancement of current Jupyter tools which includes:
- Jupyter Notebook
- Jupyter console (not QTConsole)

Along with other useful programming tools such as:
- Local Terminal (Linux, Windows, Mac)
- Text Editor
- Directory (IDE style)

In my previous experience of Jupyter notebook usage, I always suffers from change the focus between different Windows, alt+tab to find log monitoring terminal, alt+tab to test a snippet of code in another console to see if it works, alt+tab to check whether model persistance file is generated, etc.

Unless you had a very clear mind where are looking for, otherwise, you will easily lost in the forrest of windows/tabs......

That is something I am not quick happy about, but it is also a painful story to jump back to IDEs, where Jupyter Notebook is becoming part of my development habit.

Jupyter developers feels that pain and bring in the JupyterLab, a tool that is not an IDE but has most IDE features, also, it is not a typical Notebook, but notebook is a part of it.

So, let's walk through the Jupyter Lab to see what does it offers.

## Prerequisites
- Local PC or remote virtual machine.
- Jupyter notebook version higher than 4.3.
```python
jupyter notebook --version
```
an update for **notebook** package is recommonded.
- check the jupyter realted package is installed such as:
2. jupyter                  
2. jupyter_client           
2. jupyter_console          
2. jupyter_core             
2. notebook                 

## Installation
Check [JupyterLab installation](http://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html), consist all the methods for installation. For me, I use 
```python
pip install jupyterlab
```
for Windows, and use
```python
conda install -c conda-forge jupyterlab
```
for remote Linux virtual machine.

After installation, the following package shall be in your virtual env:
2. jupyterlab                0.32.1                   py35_0    conda-forge
2. jupyterlab_launcher       0.10.5                   py35_0    conda-forge

## How to Use
In CLI, type
```python
jupyter lab
```
the following IDE interface shall appear on your local web browser, just like notebook
![The interface of jupyter lab in browser](/images/overall.png)

## What is different?