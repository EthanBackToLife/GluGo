# Introduction

This folder contains the code and associated files to run the glucose prediction algorithm. 

# Contents

#### dataAccess.py

This module contains the team's functions for interacting with 
the database.

#### gluPredict.csv

This CSV file contains a table displaying the actual and the 
predicted glucose values from mid-May to mid-June.
 
#### lab.db

This file contains the database with the machine learning group's 
added columns.

#### ml.py

This program imports a set of sensor data from the database, 
generates a predicted value for each time in the data set, 
and and exports the predicted glucose values and the actual values 
to a .csv (generated gluPredict.csv).

#### ML_Documentation.pdf

This PDF explains the predictive algorithm coded in ml.py.

#### plotly.py

This program imports gluPredict.csv and generates a timeseries graph 
(via Plotly) of the predicted and actual glucose values.

#### README.md

This file is README.md.
