# ENDB2 SESSION 05

This contains solution to END Batch 2 Seesion 05

## OBJECTIVE 

### StanfordSentimentAnalysis 

We need to do sentiment analysis for StanfordSentimentAnalysis  .

This dataset contains just over 10,000 pieces of Stanford data from HTML files of Rotten Tomatoes

Labels are 0, 1, 2, 3, 4 

meaning : {0:'Very Negative', 1:'Negative', 2:'Neutral', 3:'Positive', 4:'Very Positive'}

### TASK 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/ASSIGNMENT.PNG" align="center" height="388" width="757" ></a>


### GITHUB LINK 

https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/04_Sentiment_classification_SST_Glove_Final.ipynb


### HOW TO PREAPRE DATASET 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/CREATE_DATASET.PNG" align="center" height="523" width="1097" ></a>


### DATA AUGMENTATION STRATEGY 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/DATA_AUGMENTATION.PNG" align="center" height="517" width="497" ></a>

### DATA CLEANING STRATEGY 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/DATA_PREPROCESSING_CLEAN.PNG" align="center" height="223" width="606" ></a>


### EMBEDDING 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/GLOVE_EMBEDDING.PNG" align="center" height="86" width="391" ></a>

### LSTM MODEL 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/MODEL_MULTI_LAYER_BIDIRECTIONAL.PNG" align="center" height="155" width="476" ></a>


### TRAIN TEST LOG 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/TRAIN_TEST_ACC_LOSS_LOGS.PNG" align="center" height="514" width="286" ></a>


### TRAIN TEST LOG IMAGE 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/TRAIN_TEST_ACC_LOSS_IMAGE.PNG" align="center" height="439" width="660" ></a>


### CONFUSION MATRIX 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/CONFUSION_MATRIX.PNG" align="center" height="422" width="482" ></a>


### CORRECTLY CLASSIFIED SAMPLE 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/CORRECT_CLASSIFIED_SAMPLES.PNG" align="center" height="469" width="1268" ></a>

### INCORRECTLY CLASSIFIED SAMPLE 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-05/images/INCORRECT_CLASSIFIED_SAMPLES.PNG" align="center" height="465" width="927" ></a>


## LEARNING 

01 . As sentences are too small in length  do not apply too much text cleaning 

02 . Using Embedding Glove increased accuracy from 30 % to 40 % 

03 . Model mostly confuse between positive <--->  very positive  and negative <----> very negative 

04 . Can be increased accuracy by separating positive <--->  very positive   and negative <----> very negative 
