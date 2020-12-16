# DNN2

# About Data
The data includes stats from an insurance company. The label of the data has 2 categories 
0 and 1. 0 is if the cutomer will not purchase the inusrance and 1 is that the cutomer will purchase the insurance 

# Preprocessing
as the data was unbalanced oversampling was done througha package called imblearn
then the label data was converted into one hot encodings
then the data was split

# Model
A basic dense neural network models were implmented to predict the label of the data
The first model contains only 1 layer and has the lowest capacity
The second model has 2 layers having a higher capacity 
and the third model contains some regularization to limit the capacity

The models are compared at the end to see which model performd the best
