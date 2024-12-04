# Welcome to our SC1015 Course Project
## About 

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) called "X-Ray Classification of Lung Images for Pneumonia  Detection" which focuses classifying lung x-ray images taken from the Mendeley dataset.

Link here: https://data.mendeley.com/datasets/rscbjbr9sj/3. 

For detailed walkthrough, please view the source code in order from:
1. Data Collection
2. Data Preparation
3. Data Exploration
4. Classifying using Decision Trees
5. Classifying using Logistic Regression
6. Classifying using Deep Learning - Convolutional Neural Network
7. Comparing and Evaluating Models
8. Improvements to our method

We have also included the slides for our project

## Problem Definition
Classifying if a chest xray is normal or depicts that the person has pneumonia



## Models Used
1. Decision Trees
2. Logistic Regression
3. Neural Networks

## Conclusion
1.  Convolution Neural Network worked best for us.
2.  The True Negative Rate or the Accuracy is low throughout the models which is occuring because of imbalance class data.
3.  Note that Pneumonia has 2x more data than normal. Therefore one of the solutions is to reduce the Pneumonia to be same size of Normal, but it has a drawback that       we then will lose a lot of data. Also, we need to modify the Loss function during training such that the penalty for misclassifying "normal" is more.  

## What did we learn from this project?
1. How to translate images to numbers, filtering images through convolutional matrices 
2. Selecting depth of Classification Tree by running cross validation
3. Logistic Regression from sklearn
4. Convolutional Neural Networks
5. Collaborating using GitHub
6. Concepts about Transfer Learning through Resnet
7. How to zoom, shift the images to make the model more robust

## References
1. Kermany D, Goldbaum M, Cai W et al. Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning. Cell. 2018; 172(5):1122-1131. doi:10.1016/j.cell.2018.02.010.
2. https://towardsdatascience.com/how-to-find-decision-tree-depth-via-cross-validation-2bf143f0f3d6
3. https://www.youtube.com/watch?v=0HDy6n3UD5M
4. https://github.com/Pitsillides91/Pyth... 
5. https://www.researchgate.net/figure/Calculation-of-Precision-Recall-and-Accuracy-in-the-confusion-matrix_fig3_336402347
6. https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
7. https://math.dartmouth.edu/~m70s20/ImageAnalysis.pdf


