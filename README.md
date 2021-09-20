Neurips XAI Workshop 2021 Code Submission for Paper "Interpretability in Gated Modular Neural Networks"
=======================================================================================================

Code for reproducing results in the paper

REQUIREMENTS
------------

1. ``Python 3.7`` (or above)
2. Linux Operating System. It has been tested on MacOS. 
3. Additional modules listed in ``requirements.txt``

INSTALLATION 
------------

In order to install the code locally please follow the steps below:

1. Clone this repository and go to the cloned directory.

2. Set the environment variable to point to your python executable:

   `export PYTHON=<path to python executable>`

3. Run the following command to set up the environment:

   `make -f Makefile.linux` on **Linux/Mac**

4. Activate the environment by running:

   `source xai2021/bin/activate` on **Linux/Mac**


RUNNING JUPYTER NOTEBOOK
------------------------

1. Run jupyter notebook (the xai2021 env is already loaded in the ipykernel):

   `jupyter lab`

2. In the jupyter lab open either the toy_classification.ipynb or mnist_classification.ipynb notebooks.

3. Select the xai2021 kernel.

4. You should now be able to run the notebooks.

