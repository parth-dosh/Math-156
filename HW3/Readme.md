Math 165 - Homework 3. Parth Doshi. UID - 805623259. February 3, 2025. 

Question 3: 

I worked on this question by myself. This question implements my binary logistic regression using mini-batch SGD, following Equation 4.90 from the textbook. I trained the model by iteratively updating weights based on small batches of data while improving efficiency and reducing the risk of getting stuck in the local minima. The sigmoid function maps the inputs I gave it to probabilities, while the cross-entropy loss measures the prediction error. During training, the data is shuffled, the mini-batches are processed, and the weights are updated using gradient descent with a fixed learning rate.

The model I created supports key functions for prediction and evaluation, including probability estimation and performance metrics such as accuracy, precision, recall, and F1-score. The evaluate function provides an assessment of model performance and ensures reliable results. The three main are hyperparameters—batch size, learning rate and max iterations allow for fine-tuning the training behavior. 


Note: Question 4's results were explained in markdown form in the ipynb file for Q4 part f. 
