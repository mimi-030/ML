
> In this exercise, Homework 3 will focus on two main topics for non-Deep Learning analysis, while Homework 4 will focus on the following two main topics for Deep Learning analysis.
Non-DL refers to traditional machine learning methods that are not based on deep learning.Non-DL refers to traditional machine learning methods that are not based on deep learning.


## Homework3

### 1. the Adult (A) dataset
[To Get Dataset🔗](https://archive.ics.uci.edu/ml/datasets/Adult "To Get Dataset🔗")

Method 1: Decision Tree
Method 2: SVM

[ 👉code for the Adult (A) dataset](https://github.com/mimi-030/ML-DL-Practices-for-Beginners/blob/main/Homework3/adult_nonDL.ipynb " 👉code for the Adult (A) dataset")

------------



### 2. the Spooky Author Identification (SAI) dataset
[To Get Dataset🔗](https://www.kaggle.com/c/spooky-author-identification "To Get Dataset🔗")

Method 1: Decision Tree
Method 2: SVM

[ 👉code for SAI dataset](https://github.com/mimi-030/ML-DL-Practices-for-Beginners/blob/main/Homework3/spooky_author_nonDL.ipynb " 👉code for SAI dataset")

------------


**[ 📄 Full Report of non-DL](https://github.com/mimi-030/ML-DL-Practices-for-Beginners/blob/main/Homework3/README.md " 📄 Full Report for non-DL")**

------------


## Homework4

### 1. the Adult (A) dataset
[To Get Dataset🔗](https://archive.ics.uci.edu/ml/datasets/Adult "To Get Dataset🔗")

Method 1: DNN
Method 2: RNN

[ 👉code for the Adult (A) dataset](https://github.com/mimi-030/ML-DL-Practices-for-Beginners/blob/main/Homework4/adult_DL.ipynb " 👉code for the Adult (A) dataset") 

------------


### 2. the Spooky Author Identification (SAI) dataset 
[To Get Dataset🔗](https://www.kaggle.com/c/spooky-author-identification "To Get Dataset🔗")

Method 1: DNN
Method 2: CNN

[ 👉code for SAI dataset](https://github.com/mimi-030/ML-DL-Practices-for-Beginners/blob/main/Homework4/SpookyAuthor_DL.ipynb " 👉code for SAI dataset")

------------

**[ 📄 Full Report for DL](https://github.com/mimi-030/ML-DL-Practices-for-Beginners/blob/main/Homework4/README.md " 📄 Full Report for DL")**

------------

## Comparison between DL and non-DL:  (Homework3 vs. Homework4)

### I. Spooky Author Dataset
DL methods used were DNN and RNN, while non-DL methods used were Decision Tree and SVM. The accuracies are:
1. DNN: 74%
2. RNN: 82%
3. Decision Tree: 46%
4. SVM: 72%

It can be observed that RNN has the highest accuracy of 82%, followed by DNN with an accuracy of 74%, and SVM with an accuracy of 72%. RNN is the most suitable for this dataset, followed by DNN and SVM. However, Decision Tree is not suitable for this dataset with an accuracy of only 46%. Therefore, this dataset may be more suitable for training using deep learning methods.

### II. Adult Dataset
DL methods used were DNN and CNN, while non-DL methods used were Decision Tree and SVM. The accuracies are:
1. DNN: 85%
2. CNN: 86%
3. Decision Tree: 85%
4. SVM: 79%

It can be observed that CNN has the highest accuracy of 86%, followed by DNN and Decision Tree with an accuracy of 85%, and SVM with an accuracy of 79%. Regardless of using CNN, DNN, or Decision Tree, these methods are suitable for training this dataset, with SVM being the least suitable. Overall, the accuracies obtained using these methods are good. Deep learning methods provide good accuracies, but non-DL methods can also be used for training and are easier to implement.

### III. Conclusion
Comparing the two datasets, Decision Tree has an accuracy of 85% in the Adult Dataset, which is a good training result, but only 46% accuracy in the Spooky Author dataset, indicating that it is not suitable for this dataset. DNN performed well in both datasets. It can be concluded that Spooky Author is more difficult to predict with generally lower accuracies, while deep learning methods provide good results for both datasets. The Adult Dataset is easier to predict, and non-DL methods can also provide good results.


