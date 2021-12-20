# Final_term
기말과제


In this project, we were supposed to use various scikit learn package in order to find the best accuracy through training. We have learned Perceptron, Logistic regression and how to apply them to olivetti face. Olivetti faces are face images taken between April 1992 and April 1994 at AT&T Laboratories Cambridge, and they are images quantized to 256 grey levels and stored as unsigned 8-bit integers. Basically, the loader will convert these elements into floating point values on the interval [0,1]. The reason is that the conversion makes the work easier for various algorithms. The main purpose of this database is an integer from 0 to 39, indicating the identity of the person. Usually, the original dataset consists of 92 x 112, but the training dataset we used were only 64x64 images. Using this dataset, we were assigned to employ any machine learning algorithm implemented in the scikit learn package to find which machine with which hyperparameter can achieve high accuracy rate after training.

The algorithm I have chosen is Logistic regression. Logistic regression is a linear model for classification rather than regresion. From this model, we can see what the probabilities describe as they show possible outcomes of trials.

In this assignment, there were usage of hyper-parameter of the function. However, the they were set in default, which resulted in low accuracy rate. In order to improve the training progress, we were supposed to tune some of the hyper-parameter of the function. I have changed "C" and "max_iter" in order to give a change to accuracy rates. In Logistic Regression, there are multiples of hyper-parameters that can be changed however, there were some of the variables that couldn't be changed nor give any change to accuracy value. For the parameter "C", this changes regularization intensity. The lower the value of C is, the closer it goes to 0, which enhances regularization. "Max_iter" is simply limiting the number of repetition in finding the solution. Therefore these were some information about the final project that we did in Open Source Course.


