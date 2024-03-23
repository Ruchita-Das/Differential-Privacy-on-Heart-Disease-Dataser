# Prediction of Heart Disease Using Differential Privacy


This repository contains the heart disease dataset and prediction of it using neural networks.
There are two other files where laplacian and gaussian noise has been added to privatise the data before sending it for training and then seeing different observations.

Observations were-

1.By adding noise to the dataset,the accuracy of the model decreases.

2.Adding the noise column wise leads to similar value for similar data hence making it susceptible to attacks.

3.Adding noise row wise makes the data more discrete and the randomness of the datamakes it far less susceptible to attacks,i.e. makes the data more differentially private

4.By varying the value of the privacy budget(eplison) we see that there is a sharp increase in the accuracy at first but after a certain point,the accuracy becomes almost constant and does not rise.

5.By varying the standard deviation(sigma) we see that there is a gradual decrease in the accuracy of the model.
