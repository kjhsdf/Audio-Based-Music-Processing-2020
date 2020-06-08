Adapted from: Erlangen Audio Labs Jupyter Notebook - "Installing and Testing a Python Environment"

Install Python 3.6 Miniconda (<https://conda.io/miniconda.html>) with default settings. Then open an Anaconda-aware command line interface (e.g. Anaconda Command Prompt in Windows, standard Terminal in Linux/OS X).

Install Jupyter using Conda:

```
conda install -c conda-forge notebook
```

Step into the directory containing the provided files `environment.yml` and `mircourse_install.ipynb` and create a Python environment (named `FMP`) for this course. You may confirm on demand. Also note it could take a while.

```
conda env create -f environment.yml
```

Activate your environment with the following command:

```
conda activate FMP
```

Now run the following command to start Jupyter.

```
jupyter notebook
```

Your default browser should open and show the current directory. If it does not, open your browser and go to <http://localhost:8888>. There you can open a notebook by clicking on its file name.