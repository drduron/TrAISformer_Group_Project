# TrAISformer_Group_Project 
---
Group: 5 

By: Abigail Basener, Dimitri Duron, Dana Louie

# Overview
This project holds the code to train and test a TrAISformer on 3 different datasets around the USA east cost. 
The original repo from the paper that we recreate the resalts of and test on our data can be found at https://github.com/CIA-Oceanix/TrAISformer.git

# Files
Each dataset has a folder containing the required code.

## Northeast:
- *Setup-NE.ipynb:* This is the main file that can will download the repo, make any needed changes and run the model on the original data. Then run the model on new data. Then it will generate needed plots.


## Midatlantic:
data_prep.ipynb is intended to run with the original csv file in the same directory. Then run trainer_analysis.ipynb in the same directory. 
- *data_prep.ipynb*: Prepares and processes the Mid-Atlantic AIS dataset for use with TrAISformer. The notebook handles the data processing steps needed to transform the raw AIS data into a format suitable for model training and evaluation.
- *trainer_analysis.ipynb*: Analyzes the results and performance of the trained TrAISformer model on the Mid-Atlantic dataset. The notebook is used to examine model outputs and evaluate the resulting trajectory predictions.

## Florida:
- *Setup-FL.ipynb:* This is the main file that can will download the repo, make any needed changes and run the model on the original data. Then run the model on new data. Then it will generate needed plots.

## Other
- This *README* explaining how to use the repo
- *Main.ipynb* which can run the best Northeast and Florida model and test data specifically to reproduce the results without having to retrain. 

# Required
- Python 3.11.6
- **Data**
  *Use the google drive to get the data we used in this project*
  - the AIS... file is the raw data
  - the other files are required for the run of *main.ipynb* they should be kept in their corresponding sub folders, and the folders moved to where *main.ipynb* is to be run.
- packages:
    torch, torchvision, torchaudio, numpy, pandas, scikit-learn, scipy, tqdm, einops, pyyaml, matplotlib, cartopy
- Internet accesses to git clone needed files
