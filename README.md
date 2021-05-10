# Hand-written-digit-recognition
# Here we will use standard MNIST dataset,where data will be in numerical(pixel)values format,total there are 28*28=784 pixels
# Initially we will check wheather there are any null values or not, later we will do  feature scaling on data
# After this ,all pixel value will be between -1 and 1 only, now we will do label encoding to get y values from 0 to 9
# we have to repeat same process for test data also mentioned above
# Here we will use k nearest neighbours algorithm to classify them into 10 categories, here we take n_neighbours=1 
# now we will train this model with standard train data and we will make predictions on test data using this model
