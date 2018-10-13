# Typhoons-and-Hurricanes-Hacknight #

Materials for the JBCA Hacknight on the 22nd March. 
The aim of this tutorial is to demonstrate how to predict hurricanes from temperature data, and the importance of a balanced dataset. 


This project contains the following notebooks, so you need Jupyter Notebook to run the tutorial:
1. Make_Features_and_Labels.ipynb
2. Deep_Learning_to_Predict_Hurricanes.ipynb
3. NN_with_F1_score_77percent.ipynb

## Prerequisites ##
### Creating and Activating an Environment ###
Create and activate an environment for the project using the following commands
To create an environment 
```
conda create -n myenv python=3.5 
```
or the python version you require

To activate the environment 
on Windows
```
activate myenv
```

on Linux and MacOS
```
source activate myenv
```

More on handling environments can be found here:
https://conda.io/docs/user-guide/tasks/manage-environments.html#activating-an-environment


### Installing Required Packages ###
The following packages are required for running the project, install them in the environment you created above
```
conda install -c conda-forge basemap

conda install -c conda-forge pyproj

conda install -c conda-forge basemap-data-hires

conda install -c conda-forge keras tensorflow
```
Make sure that you have Typhoons-and-Hurricanes-Hacknight folder existing the environment folder, and that you are running the notebook with the environment kernel

## Running the Project ##
* First run the Make_Features_and_Labels.ipynb, so the dataset will be ready for the other notebooks.
* Then run the Deep_Learning_to_Predict_Hurricanes.ipynb to appreciate the importance of a balanced training dataset, and tryout ways to address the issue.
* Then run the NN_with_F1_score_77percent.ipynb to see the results when the issue of overfitting is addressed.

