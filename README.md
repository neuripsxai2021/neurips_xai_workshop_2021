Neurips XAI Workshop 2021 Code Submission
===========================================

Code for reproducing results in the paper

REQUIREMENTS
------------

1. ``Python 3.7`` (or above)
2. Linux Operating System. It has been tested on MacOS. 
3. Additional modules listed in ``requirements.txt``

INSTALLATION 
------------

In order to install the code locally please follow the steps below:

1. Create a local working directory for the repository and navigate to it within your terminal or command prompt window.

2. Clone this repository.

3. Set the environment variable to point to your python executable:

   `export PYTHON=<path to python executable>`

4. Run the following command to set up the environment:

   `make -f Makefile.linux` on **Linux/Mac**

5. Activate the environment by running:

   `source xai2021/bin/activate` on **Linux/Mac**


RUNNING JUPYTER NOTEBOOK
------------------------

1. Run jupyter notebook (the xai2021 env is already loaded in the ipykernel):

   `jupyter lab`

2. In the jupyter lab open either the toy_classification.ipynb or mnist_classification.ipynb notebooks.

3. Select the xai2021 kernel.

4. You should now be able to run the notebooks.

