# Analysis of Chest X-Ray images
> build a neural network model using to identify X-Ray images where an "effusion" is present

 

# Problem statement
> Neural networks have revolutionised image processing in several different domains. Among these is the field of medical imaging. In the following notebook, we will get some hands-on experience in working with Chest X-Ray (CXR) images.

The objective of this exercise is to identify images where an "effusion" is present. This is a classification problem, where we will be dealing with two classes - 'effusion' and 'nofinding'. Here, the latter represents a "normal" X-ray image.

This same methodology can be used to spot various other illnesses that can be detected via a chest x-ray. For the scope of this demonstration, we will specifically deal with "effusion".


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect abnormalities in the X-ray scans.
- Neural networks have revolutionised image processing in several different domains. Among these is the field of medical imaging. In the       	following notebook, we will get some hands-on experience in working with Chest X-Ray (CXR) images.

- The objective of this exercise is to identify images where an "effusion" is present. This is a classification problem, where we will be  	dealing with two classes - 'effusion' and 'nofinding'. Here, the latter represents a "normal" X-ray image.

- The dataset consists of X-ray scans, which were formed from the CXR datasets.



## Steps Followed in the Projects
- Data Preparation: Made sure all our images were of the same resolution
- Data Pre-Processing: Morphological Operations
- Data Pre-Processing: Normalisation
- Data Pre-Processing: Augmentation
- Model Building: Choosing AUC as evaluation metrics & introducing weighted cross entropy 
- Running ablation experiments
- Overfitting on a smaller version of the training set
- Hyperparameter tuning
- Mode training and evaluation



## Conclusions
- Accuracy has been improved significantly after treating the class imbalance using augmentation.
- ROC has been improved by using weighted cross entropy for loss validation.
- Accuracy 80% and AUC 84%, with very less loss in train and validation.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- pathlib
- keras
- tensorflow
- matplotlib


## Acknowledgements
Give credit here.
- I would like to thank my upGrad Buddy and tutor for assisting me to complete this assignment
- Reference: Stack Overflow, Wikipedia & Google Collab 


## Contact
Created by [@subham0206] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [https://github.com/subham0206/Analysis-of-Chest-X-Ray-images.git](). -->
