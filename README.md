# Neural_Network_Charity_Analysis


#OVERVIEW OF THE ANALYSIS AND PURPOSE

Module 20 teaches us about tensorflow in Python. It also teaches us how to implement neural networks using tensorflow and how to apply that to deep learning. We practiced implementing neural networks and deep neural networks on different data sets like this one called charity data. Our goal was to try to get the accuracy as high as we could. Even though neural networks are not perfect and will underperform we can help by looking at input data set, add more neurons to a hidden layer, additional hidden layers, use different activation function for the hidden layers, or even add additional epochs to the training regimen.  We used data based on alphabet soup charity from this module. Our goal was to gauge lending amounts and who or what companies are safe to lend money to.

#RESULTS
DATA PREPROCESSING
The variables that are considered the targets in our model were quantitative data and categorical data.

The features in our model
were types such as application type affiliation, classification, status, income amount, special considerations, and the like.

The variables that are neither targets nor features and were removed were name, ein. But I'm not sure if that was a good idea.
![image](https://user-images.githubusercontent.com/115684964/224512651-a2cd5e26-7150-4ee8-a07b-2e6781d6f5cc.png)

First attempt
![image](https://user-images.githubusercontent.com/115684964/224512709-01aa89f7-56a3-4313-8dd6-47b1b9919ef5.png)


COMPILING TRAINING AND EVALUATING THE MODEL
I started with one layer and went to three. I also used relu.  My number of neurons also changed in all three examples between 12 and 50. I was not able to achieve 75% accuracy, however. These are the steps I took to try and increase model performance. I understand that the activation function decides whether neurons should be activated or not and is related to bias. However, I'm not sure what the activation function is in my model except for Relu, and Tanh which we changed and used.
The main things we needed to do to improve our data we needed the name back in and to change the binning sizes.
3rd attepmt
![image](https://user-images.githubusercontent.com/115684964/224512685-41484f55-be6b-4a83-b768-35a7e75d968a.png)


