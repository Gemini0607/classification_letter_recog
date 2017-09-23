# Classification - Letter Recognition

1. Source Information

The description of the dataset can be found in the description.txt file. The data set was downloaded from the UCI Machine Learning Repository.

2.The Approach

Classification was performed with(letter_recognition_pca.ipynb) and without(letter_recognition) using Principle Components Analysis. The objective was to develop a robust model that would correctly classify the given characters, and use parameter tuning to improve the performance of the model, and also study the effect of PCA on model performance.

3. Technique used

-- We have made of use of Linear models, tree based model, Support vectors and Nearest Neighbour to build the the best possible classifier.
-- Out of the following, the best results were obtained using KNN Classifier(default parameters - 95.4 and tuned model - 96.12) and Extra Tree Classifier(default parameters - 94.24 and tuned model - 97.32). 
-- These were the accuracies without applying PCA (all 16 feature variables).

-- After applying PCA(using only 14 feature variables), there was only slight decrease in model performance.
-- KNN Classifier(default parameters - 95.04 and tuned model - 95.7) and Extra Tree Classifier(default parameters - 95.53 and tuned model - 96.08).

-- Since this was a multilabel classification problem, a classification report containing precision, recall, f1-score and support could be generated, as AUC ROC are applicable to binary classification outputs. 
