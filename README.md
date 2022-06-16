# Network Anomaly Detection Systems via Machine Learning
  The evolution of computer networks has greatly increased computer security concerns, especially internet security in 
today's networking environment and advanced computing facilities. Cyber security is the set of technologies and processes
designed to protect networks, computers, programs and data from digital attacks. Network intrusion detection systems
(NIDS) are one of the network security technologies that analyze incoming network traffic. Anomaly detection, as a main 
part of Network intrusion detection systems, aims to discover patterns in data that do not conform to the expected normal 
behaviour. Since abnormal activities are seen around 1% in datasets such as intrusion detection datasets, it has been 
generally observed that the imbalanced datasets have fewer positively labeled samples than negative ones. Most machine 
learning classification algorithms don’t work efficiently on these rare event datasets. One may observe a high accuracy 
in total in classification models, but these results may be misleading due to the very low number of minority classes. In 
this project, we evaluated the performance of the following class imbalanced strategies and machine learning 
algorithms and compared their performance result.
 
Class imbalanced strategies:
* SMOTE
* SMOTEENN
* Tomek Link
* Adasyn
* Random oversampling (ROS)
* Random undersampling (RUS)
 
Used Machine Learning Algorithms:
* SVM
* RandomForest
* XGBoost
* LogitBoost

In "totalresults.xlsx", you can see the performance results for this research in one table. Performance is measured by accuracy, precision, recall, TPR, FPR.

In "papertable.xlsx", you can see the literature review, done for this project. You can see the algorithms and their accuracy, FPR and TPR rates.(If they're written in source paper) 
