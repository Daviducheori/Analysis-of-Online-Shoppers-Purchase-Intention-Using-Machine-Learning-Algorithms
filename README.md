# Analysis-of-Online-Shoppers-Purchase-Intention-Using-Machine-Learning-Algorithms


### Project Overview
The use of online stores has grown significantly around the world in recent years. Having the ability to automatically determine a user's purpose is one of the essential elements in facilitating real-time decision-making for products and enterprises. This paper studies selected classification algorithms on an online shopper purchasing Intention dataset, identifies the key parameters that are crucial for anticipating a shopper's behaviour and therefore develop a system which can perform prediction of online shoppers’ intention with a higher accuracy. The findings of this research may have an impact in offering crucial recommendations and performance enhancements on those measures. The algorithms considered in this study are a conventional machine learning algorithm in which Random Forest was used, Neural Network, and implementation in Azure. The classifiers are evaluated based on accuracy, precision, recall and F1 score. In addition, algorithms were discussed and also compared to identify the most accurate classifiers.

### Dataset
The dataset used in this research is the “Online Shoppers Purchasing Intention” data and it was retrieved from the University of California, Irvine, a well-known website giving access to thousands of datasets for study. The dataset consists of 12,330 entries and 18 columns and 1 class label called Revenue which contains either a True or False value. It seeks to ascertain online consumers' intentions. The creators of the dataset are C. Sakar and Yomi Kastro, and the original dataset can be obtained at the link below.
https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

### Exploratory Data Analysis

- Univariate Analysis
- Multivariate Analysis: Correlation Plot of the Dataset
- Exploration of Specific Variables

### Explanation and Preparation of Dataset
- Installing the Libraries: The most well-known Python libraries, such as Pandas, Seaborn, Matplotlib, and others, were first be imported into the project. 
- Null and Missing Values
- Checking for Outliers
- Duplicate Data
- Class Imbalance
- Label Encoding

### Evaluating the Model
  

### Machine Learning Algorithm Used
- Random Forest
- Neural Network (Keras)
- Implementation in Azure
  
### Implementation in Python
- Data Splitting
- Normalisation
- Feature Selection
- Hyperparameter Tuning

### Implementation in Azure
- Creating a Workspace
- Creating a Compute Cluster
- Creating a Pipeline
- Importing the Dataset
- Adding Dataset to Canvas in Pipeline
- Data Pre-processing: Normalisation
- Class Imbalance
- Adding Training Modules: Data Splitting
- Training Model and Selecting the Column to Predict
- Algorithm: Two-Class Neural Network
- Scoring Model
- Evaluating the Model

### Result and Discussion
According to accuracy, precision, F1 score, and recall results of four algorithms utilised in this study.  Keras leads the other three algorithms in terms of accuracy, scoring 90%, while the Two-Class Neural Network implemented in Azure scores the least accuracy, scoring 84%.
It should be noted that the Random Forest still has the lowest precision rate, at 76%, while the Two-Class Decision Forest has the greatest percentage, 91%. Recall performance rates for the four algorithms range from 75% for Keras to 95% for the Two-Class Neural Network, with 95% being the best. 
The classifier with the highest precision and recall was determined using the F1 metric. The conjuction of recall and precision is known as the F1 score. According to this performance metric, it is clear that Two-Class Decision Forest has the highest F1 measure (92%), whereas Keras has the lowest F1 measure (78%), which is due to its extremely poor recall rate of 75%.

### Conclusion
The goal was to identify a suitable model that could more reliably predict a customer's purchasing intent when they visited an online store's website.  The optimal algorithm to use for a particular data mining task can be difficult to choose. The ideal method is to do a performance validation of various algorithms to select the best one that produces the desired outcome. Comparative examination of the four classifications methods were done in this study. In order to find the best prediction model, the different classification algorithms were contrasted on the basis of the metrics accuracy, precision, recall, and F1 score. Due to its superior performance compared to all three algorithms in the majority of the performance indicators evaluated in this study, Two-Class Decision Forest in Azure is effective at forecasting a customer's propensity to make a purchase.






