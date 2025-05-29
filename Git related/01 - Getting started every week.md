# Installing anaconda, github and jupyter lab

Before we start class, you will need to install Anaconda, Git, and Jupyter Lab. Anaconda is a user-friendly python environment that allows you to run jupyter notebooks and publish your work throughout the quarter to GitHub via the [git extension](https://github.com/jupyterlab/jupyterlab-git). 

* Install [Anaconda](https://www.anaconda.com/download). 

* In your search bar, type in `anaconda prompt`. 

<kbd><img src="images/conda.png"></kbd>

* Next, install the git extension via these two methods [#1](https://github.com/jupyterlab/jupyterlab-git?tab=readme-ov-file#install) or [#2](https://anaconda.org/conda-forge/jupyterlab-git). Both work! Type on the `conda install` command to the anaconda prompt, hit enter, select Y. 

<kbd><img src="images/conda1.png"></kbd>

* Anaconda should have jupyter lab installed by default. To start `jupyter lab` after installing the `git extension` type `jupyter lab` and hit enter. A local internet browser will open. 

<kbd><img src="images/conda2.png"></kbd>

<kbd><img src="images/conda3.png"></kbd>

# Getting started each week
At the start of each week, you will be asked to update the class repository. Note that this is different from your own personaly repository. To do so, follow these instructions.

First, we will clone the course repository and then run a "pull" each week to download the latest course material into JupyterLab.

* Install the [GitHub extension for Jupyter Lab in the Anaconda terminal](https://github.com/jupyterlab/jupyterlab-git?tab=readme-ov-file#install)
<kbd><img src="images/gitExt.png"></kbd>

* After installing the Git extension, type into the terminal `jupyter lab` to start a local notebook.

* Copy the course GitHub clone HTTPS link.

<kbd><img src="images/gitHTTPS.png"></kbd>

* Paste the course GitHub clone HTTPS link --> Git --> Clone a Repository --> Paste link --> Clone

<kbd><img src="images/gitURL.png"></kbd> 

Note that the link above (git puller) follows the [following set of rules](https://jupyterhub.github.io/nbgitpuller/topic/automatic-merging.html#topic-automanbltic-merging).

* We will change the directory via the `cd` command and copy the path to the course repository. Then, we will run `git pull` to download weekly course updates. 

<kbd><img src="images/conda4.png"></kbd> 
