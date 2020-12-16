# DNN2

# About Data
The data includes stats from about 615 patient blood reports 
the label data contains 5 classification 
0: Blood DONOR
0s: suspect Blood DONOR
1: Hepatitis
2: Fibrosis
3: Cirrhosis

# Preprocessing
as the data was unbalanced oversampling was done througha package called imblearn
then the label data was converted into one hot encodings
then the data was split

# Model
A basic dense neural network model was implmented to predict the label of the data 
