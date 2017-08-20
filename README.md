# Quora question duplicates
GitHub repository for my solution of Quora Question Pairs competition hosted on Kaggle (https://www.kaggle.com/c/quora-question-pairs). In this competition teams were asked to build a model to identify whether given two questions have the same intent. 

If order to reproduce our solution you will have to download train and test datasets from Kaggle (https://www.kaggle.com/c/quora-question-pairs/data) and run repository notebooks in implying order. However you may skip notebooks with ‘optional’ in their name. 

# Solution overview
My team solution was placed 13th among 3300 teams. Our best model was single LightGBM with heavy post-prediction calibration. This repository contains only my part of the solution lacking LSTM and FTR neural nets OOFs, graph features and some of the NLP features.

In this competition I used only MacBook Pro 2012, total time needed to run the code in parallel on 6 cores is about 4-5 days. The most computationally expensive parts are NLP feature generation, feature and model selection and OOFs calculation. Main model on generated features is fitted and calibrated in just 2-3 hours.
