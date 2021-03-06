# d2l.ai-learning

Repo. for learning artificial intelligence textbook found @ d2l.ai

# How to Set Up Your Environment

On the terminal:

Install `Anaconda` or `Miniconda` if you have not already.

1. `conda create --name d2l python=3.8 -y`

2. Navigate to [`mxnet`](./mxnet), [`pytorch`](./pytorch), or [`tensorflow`](./tensorflow) folder, depending on your preference.

3. `python setup.py install`

# Useful Things I Learned Along the Way

1. To get conda environments to show up for selection in Jupyter Notebook, the magic command is:

`conda install nb_conda_kernels`

on your base Conda environment.

2. To run `setup.py`, you do:

`python setup.py install` [(Stack OverFlow)](https://stackoverflow.com/questions/31373797/how-do-you-run-a-setup-py-file-properly)

3. From [2.4_Calculus](/tensorflow/Ch_02_Preliminaries/2.4_Calculus.ipynb), `d2l`'s `use_svg_display()` uses a deprecated method.

I fixed the error by setting the top statement of the first cell to:

`%config InlineBackend.figure_formats = ['svg']`
