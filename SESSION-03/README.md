# ENDB2 SESSION 03

This contain solution  of END Batch2  SESSION 03

# TASK /OBJECTIVE 


<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/TASK.PNG" align="center" height="457" width="764" ></a>



## EXPLANATION 

### ARCHITECTURE 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/ARCHITECTURE.PNG" align="center" height="202" width="1275" ></a>


### JUPYTER NOTEBOOK 

https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/MULTI_ADDER_FINAL.ipynb 

### Data Representation:

INPUT1: ONE MNIST IMAGE 
INPUT2: ONE RANDOM IMAGE FROM 0 to9 

OUTPUT 1: IMAGE PREDICTION 
OUTPUT 2: RANDOM IMAGE LABEL+RANDOM NUMBER 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/DATA_REPRESENTATION.PNG" align="center" height="23" width="348" ></a>


### Data Generation Strategy:


<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/DATA_GENERATION_STRATEGY.PNG" align="center" height="185" width="494" ></a>

### combined the two inputs

IMAGE Reduced to 1X1X10 
DIGIT Reduced to 1X1X10

then concatenated 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/COMBINE_DATASET.PNG" align="center" height="306" width="458" ></a>


### WHICH LOSS FUNCTION IS TAKEN AND WHY 

cross entropy loss :

cross entropy loss, which is basically log_softmax + nll_loss (negative log likelihood).

It is generally  used for multiclass classifcation .

### RESULT EVALUATION 

HOW RESULT IS EVALUATED 

10000 images and 10000 numbers passed through test to evaluate accuracy at every epoch 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/EVALUATE_RESULT_PART_01.PNG" align="center" height="326" width="1126" ></a>


### TRAIN AND TEST LOGS 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/EVALUATE_RESULT_PART_02.PNG" align="center" height="593" width="883" ></a>


### TRAIN TEST ACCURACY AT 30 TH EPOCH 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/ACCURACY_AFTER_30_EPOCH.PNG" align="center" height="212" width="994" ></a>


### FINAL RESULT EVALUATION FOR 1BATCH 

<a href="url"><img src="https://github.com/jitendramishra1024/ENDB2/blob/main/SESSION-03/images/EVALUATE_RESULT_PART_03.PNG" align="center" height="501" width="538" ></a>










