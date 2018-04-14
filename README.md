# Predicting Network Attack Patterns using Machine Learning Approach


## PROJECT MEMBERS
###### Abhinav Gupta( ES15BTECH11002 )
###### Adil Dangui( CS15BTECH11041 )

## OBJECTIVE
Leveraging Machine Learning approach for defining security rules on the network controller.
We compare and evaluate the performance of widely used ML algorithms on the dataset. (Classification by clustering, generative, discriminative ML approaches).
Showing that even a small probability of attack, obtained through ML approach, has significant effect on the network security.

## DETAILED DESCRIPTION OF THE PROJECT
    
###     INTRODUCTION:

A Distributed Denial of service attack is a major threat in internet. This is achieved by attackers by using multiple computers to send a flood of traffic  created intentionally to overwhelm the server resources and bandwidth.


The impact of attack varies from inconvenience to genuine users to failures of the server. Many methods have been used to detect these attacks such as using the attack trace or signature of the attack to find whether or not a request is malicious attacking packet. But getting the traces using filtering methods etc have become harder in the newer attacks. Hence there is a need of newer methods to detect the attacks with high accuracy and low magnitude of false alarms.


### METHODOLOGY:

We use machine learning (ML) algorithms to predict potential target host attacks based on the historical network attack data for KDD Cup 1999. 

#### A. Use historical data to train the ML-based modelsA. Use historical data to train the ML-based models
This database contains a standard set of data to be audited, which includes a wide variety of intrusions simulated in a military network environment. The 1998 DARPA Intrusion Detection Evaluation Program was prepared and managed by MIT Lincoln Labs. The objective was to survey and evaluate research in intrusion detection.  A standard set of data to be audited, which includes a wide variety of intrusions simulated in a military network environment, was provided.
Our goal is to use the historical attack pattern to identify the attacking/malicious packet. These predictions can be used to define security rules on network controller to ascertain the network security.

This is the complete description of the dataset under consideration. 

We train different ML algorithms (DTree, Naive Bayes clustering etc )on the dataset to predict with high accuracy a potential attack packet/host in the future.

#### B. Use the trained model to identify potential attack packets.


After the model is trained it can be used for predicting, based on which algorithm gave best results, using stratified k-fold cross validation.

As for the overall performance of one algorithm wrt other, we set two performance metrics.


	Accuracy (higher the better)
	False Alarm.(lower the better)


## LIST OF SOFTWARES, TOOLS, OPEN SOURCE PROJECTS, AND RESEARCH PAPERS


###### Dataset : http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.htmlDataset : http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html


###### Research Paper 1 (Main): Predicting Network Attack Patterns in SDN using
Machine Learning Approach. http://www.commsp.ee.ic.ac.uk/~faheem/nfv-sdn.pdfMachine


###### Research Paper 2: Machine Learning Approach for Attack Prediction  and Classification using Supervised Learning Algorithms. https://pdfs.semanticscholar.org/725d/9cb512c870aab582b82b4a5bcae0feb8b427.pdf


###### Research Paper 3: Predicting Application Layer DDoS Attacks Using


##  LIST OF DELIVERABLES:

Python source code/codes used to train,cross-validate,test the models.
Prediction accuracy of different ML algorithms for the dataset above in different training/testing split scenarios and threshold (α).
Detailed report on our study on traffic pattern of individual attacks, performance of various algorithms on the dataset. And maybe reasoning as to why one algorithm performed better than other (wherever possible).



