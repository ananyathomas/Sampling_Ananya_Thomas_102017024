# Sampling_Ananya_Thomas_102017024

Name : Ananya Thomas<BR>
Roll No : 102017024<BR>
Sub Group : CSE 1

# Introduction

In this assignment I will be :
* Converting a highly imbalanced data into a balanced data.
* Creating five samples using five different sampling techniques.
* Applying five different machine learning models on all the five samples.
* Comparing the accuracies and determining the most optimal model.

# Methodology

![image](https://user-images.githubusercontent.com/72699766/219966821-8eae5c43-fedf-43fe-a45d-bf20c70dddb1.png)


The dataset provided was highly imbalanced. To make it a balanced I used overampling on the minority class and then proceeded to create samples.


The 5 sampling techniques used were : 


*   Simple Random Sampling
*   Stratified Sampling
*   Cluster Sampling (by taking clusters on the basis of the Time column)
*   Cluster Sampling (by taking clusters on the basis of the Amount Column using K-Means Clustering)
*   Systematic Sampling

The 5 models used were :
*   KNN
*   Naive Bayes
*   Logistic Regression
*   Random Forest Classifier
*   CNN

On comparing the five models on the five samples we can conclude that :

<img width="460" alt="Screenshot 2023-02-19 at 11 43 43 PM" src="https://user-images.githubusercontent.com/72699766/219966947-9ae549b1-97b9-4bc8-bbb5-b271ce1128be.png">


The top 3 most optimal models are :
* With a **100%** accuracy
  - The Random Forest Classifier model on the sample created using Simple Random Sampling.
  - The CNN model on the sample created using Clustering Sampling technique where clusters were created on the basis of Time.
* The CNN model on the sample created using Clustering Sampling technique where clusters were created on the basis of Amount with  a **99.781662%** accuracy.
* The CNN model on the sample created using Simple Random Sampling with a **99.137932%** accuracy


The 3 worst models are :
* The Random Forest Classifier model on the sample created using Clustering Sampling technique where clusters were created on the basis of Amount with  a **57.205240%** accuracy.
* The Naive Bayes model on the sample created using Simple Random Sampling with a **63.793103%** accuracy.
* The Naive Bayes model on the sample created using Clustering Sampling technique where clusters were created on the basis of Amount with  a **67.685590%** accuracy.

