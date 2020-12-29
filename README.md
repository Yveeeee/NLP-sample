# NLP-sample

This repo contains 7 files. sklearn_NLP_sample.ipynb is the executable Jupyter notebook python file of the program and RA_task_2.pdf is the print out version of the program and the execution results. 

The original dataset has been divided into two parts. The first 76 rows of text (include the header) and their corresponding labels are in the ‘train_set.csv’ to be used as the training set for the classifier. ‘train_set_Verctorized.txt’ is the featurized version of the test set, and it could be seen as a check point file of the training process. The rest 25 rows of text without labels are saved in the ‘test_set.csv’ to perform a sample prediction of the classifier. ‘test_set_predict.csv’ is the sample file of the predict result of the classifier.

This classifier is sklearn (a python machine-learning library) Naïve Bayes algorithm based. 3 different naïve Bayes algorithms are included in the program so that we could see which one performs the best under the specific conditions.

This classifier is a vocabulary based text classifier. In terms of the natural language process, it first samples the train dataset, and generate a vocabulary list of all the words exist in the text. Then it creates a vector for every single text based on the vocabulary list. 
