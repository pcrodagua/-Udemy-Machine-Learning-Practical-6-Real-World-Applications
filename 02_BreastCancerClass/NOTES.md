# 1. Introduction
- IntroPractical Case Studies
-  PhD Engineering

#  2. Business Challenge (ML: Breast Cancer Classification using SVM )
## BC
- Breast cancer affecte 2.1 million people
- Most common cancer among woman
- Early diagnosis increases the chances of survival
- Most experience physicias can diagnose cancer with 79% accurancy
- While ML up to 91%(up to 97%) accuracy
- Classify tummors into benign or malignant

## Cancer Diagnosis Procedure
1. __Fine Needle Aspirate (FNA):__ This process extracts cells out of the tumor.
2. __Tumor Images:__ Creation of images from the FNA.
3. __Features:__ Characteristics out of the image.
	 * Radius
	 * Texture
	 * Perimeter
	 * Area
	 * Smoothness
4. __ML Algorithm:__ Feed the features into a ML model in a way that calculates the classification.
5. __Classification:__ We obtain a classifcation without human interaction.

# 3. Updates on Udemy Reviews
Done

# 4. Challenge in Machine Learning Vocabulary
## Vocabulary

![Vocabulary]4_1.png)

* __Input:__ All features extracted from the features
* __Classifier:__ Machine learning model
* __Dataset:__ All features of the instances.
* __Target:__ For this case it will be a classifier
* __Class:__ There will be two types of classes:
	* Malignant (0)
	* Benign (1)

## Support Vector Machine Classifier

![Support Vector Machine Classifier]4_2.png)

For this case, lets assume: 
* _blue dots_ are _malignant_ 
* _red dots_ are _benign_
### What we do? 
* We want the algorithm to separate the two classes using the _SVM_. This algorithm finds the best line that separates the classes.
* We take the most close dots of each class on the boundary, and call it _Support Vectors_. This are commonly the features that mostly confuses the classes.
* The line between those vectors is called _Max Margin Hyperplane_
* The Max Margin is the max distance between the two classes.

# 5. Visualization of the Data
For this part we will be focussing on the Jupyter Notebook __Breast Cancer Classification Dataset - Filming__

