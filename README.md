# NLP-Assn-2

File name | Description
--- | --- 
Train.csv | Given train dataset 
Valid.csv | Given validation dataset 
Test-format.csv | Given test data format
Assignment 2_SVM_Zheng Wanyu.ipynb | Model training script
Assignment 2_Prediction_Zheng Wanyu.ipynb | Prediction script
Train_processed | Preprocessed training dataset
Valid_processed | Preprocessed validation dataset
model.sav | Saved model used for prediction
vsctorizer.pickle | vectorizer used in model

## User Guide

1. Click into **Assignment 2_Prediction_Zheng Wanyu.ipynb**
2. Click  'Open in Colab'
3. Connect to Colab Runtime (GPU may not be necessary)
4. Run **1st** cell to clone github Repositories, now the files in thie Repositories should show up in Google Colab directory
5. Run **2nd** cell to set up environment, restart Runtime after completion
6. search for 'path_exam' to input the path where test data is stored
7. run the script from **3rd** cell, the Import Library cell, until **Output_ZhengWanyu.csv** is auto downloaded -> Output containing Predicted Labels

## Evaluation (after the .csv file is downloaded)
9. define the ground truth labels as **y_exam**
10. continue to run the Evaluation cell to output the score
