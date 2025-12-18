# Transformer_LR

This repository contains code and data for Choi et al. (under review).

Author: Seohye Choi
Last modified: 12/18/2025

# Code

Transformer-RR.ipynb: Jupyter notebook for finetuning, training, validation, and interpretative analysis of a simplified Transformer model, using datasets described below. 

LSTM-RR.ipynb: Jupyter notebook for finetuning, training, and validation of a baseline LSTM model, using datasets described below.  

# Data

data\_karst.mat: Inputs and target variables for training and validation, compiled for nine snow-dominated karst watersheds in the Western U.S. The first dimension represents each watershed in the following order:

1. Little Bighorn River
2. Salina Creek
3. Steptoe Creek
4. Lamoille Creek
5. Mission Cr. ab Reservoir
6. Cache Creek
7. Logan River
8. Red Butte Creek
9. Blacksmith Fork

data\_karst.mat: Inputs and target variables for training and validation, compiled for nine snow-dominated non-karst watersheds in the Western U.S. The first dimension represents each watershed in the following order:

1. Halfmoon Creek
2. Black Gore Creek
3. Andrews Creek
4. Minam River
5. Rock Creek
6. Bobtail Creek
7. Lake Fork
8. Stillwater Fork
9. Headwater Weber River

For both datasets, the third dimension represents 
1. Streamflow (m/d),
2. Liquid water input (i.e., snowmelt plus rain (m)),
3. PET (mm).

# Reference

Choi, S., Tennant, H., Hill, D., Neilson, B., Newell, D., Ashmead, N., McNamara, J., & Xu, T. Transformers Improve Streamflow Prediction in Karst Watersheds by Capturing Long-Term Memory Effect of Storage. Under Review.
