# generic_diabetes_classifier
Generic Classifier for Diabetes using Liner Regression Model in Tensorflow

Steps to run the program:
1. Install conda
2. Download environment.yml file your folder "workspace" (you can choose any name for this folder)
3. Go to folder in terminal (cmd in Windows) and setup Conda environment by running command : conda env create -f environment.yml
4. Activate your folder using command: activate tfdeeplearning
5. Open Jupyter notebook using command: jupyter notebook
This will open Jupyter Notebook in your browser. Navigate to your folder workspace and you should have downloaded the python code in that folder
6. Click on run all and see where you need to provide inputs


What?
This program takes a csv file named 'pima-indians-diabetes.csv' without knowing the number of columns, name of columns and datatype of columns. User will input the Classification name which should be one of the columns. Using that information, the program will use csv to train a linea classifier model to identify if the given user info have diabetes.