# Numida Exercise #

This ReadMe is primary to give instructions on how to exercute the code in this repository.
However, it is worth noting that the solution has been fully encapsulated within a jupyther notebook found 
in the source path, which is fully commented. Given that there are no project .py files, we've not added
a requirements.txt file. Howerver, we list the dependencies below.

### Packages requred for execution ###
Written as import statements for ease of reference

* import pandas as pnd
* from matplotlib import pyplot as plt
* from sklearn import tree
* from sklearn.tree import DecisionTreeClassifier as DTC
* from sklearn.metrics import accuracy_score


### How do I get set up? ###

* Set up python using (recommended) Anaconda
* Create a conda environment (give it a custom name). e.g: conda create -n tempEnv
* Install all dependencies listed above as imports. Note that scikit-learn has to be install using conda, it helps avoid ufuncs* error ussually seen when installed using pip (just FYI). Happy if you have all working fine if you used pip and all imports go through.
* The data has been added into the source path, in a folder, and referenced in the data load statemetns in the notebook.

### Contribution guidelines ###

* This code is for an assessment, not really meant for any further contribution(s).