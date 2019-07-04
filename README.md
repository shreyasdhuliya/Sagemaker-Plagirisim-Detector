# Sagemaker-Plagiarisim-Detector
## Sagemaker Linear Linear to perform binary classification

### Introduction
Training a Linear Linear Sagemaker model which examines a text file and performs binary classification 
labeling that file is either plagiarized or not, depending on how similar that text file is to a provided source text. 

Features created to train and test the model
- Containment features for n-gram ranging from 1 to 6.
- Longest Common Subsequence for each answer file compared with original source file 

### Data 
[Source](https://s3.amazonaws.com/video.udacity-data.com/topher/2019/January/5c4147f9_data/data.zip) 
- Dataframe containing 100 text files features.
- 95 Labeled answer texts with plagiarised(1) or not(0).
- 5 original source file.

### Files
1. `2_Plagiarism_Feature_Engineering` 
- Preprocessing the data
- spliting into testing and training csv files.
- Storing csv in AWS S3.

2. `3_Training_a_Model`
- Training a Linear Linear Sagemaker estimater with train data 
- DEploying Linear Linear model and predicting from the test data
- Evaluating the model using accuracy.

