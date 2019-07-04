# Sagemaker-Plagiarisim-Detector
## Sagemaker Linear Linear to perform binary classification

### Introduction
Training a Linear Linear sagemaker model which examines a text file and performs binary classification 
labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. 

Features are created bassed on
- Containment features for n-gram ranging from 1 to 6.
- Longest Common Subsequence for each answer file compared with original file 

### Data 
[Source](https://s3.amazonaws.com/video.udacity-data.com/topher/2019/January/5c4147f9_data/data.zip) 
- dataframe containing 100 text files inforamtio.
- Labeled 95 answer texts with plagiarised or not.
- 5 original answers.

### Files
1. `2_Plagiarism_Feature_Engineering` 
- Preprocessing the data
- spliting into testin gnad training 
- Storing csv in AWS S3

2. `3_Training_a_Model`
- Training a Linear Linear Sagemaker estimater with train data 
- DEploying Linear Linear model and predicting from the test data
- Evaluating the model using accuracy.

