# A--Machine--Learning--Approach--for--Drug--Sensitivity--Detection-using-Genome-Classification
genome and cell data analysis using ML

# We evaluated several classifiers consisting of Random Forest,CatBoost, Naive Bayes, Gradient Boosting, KNN, and Neural Network for predicting drug response and the sensitivity based on LN_IC50 values. These models were evaluated based on accuracy, recall, precision, and F1 score. 
 
#The CatBoost classifier the most effective model for predicting drug response and the sensitivity based on LN_IC50 values


#Dataset Description:
In this project, we are using the dataset of Genomics of Drug Sensitivity in Cancer.Here, the dataset shows extensive drug sensitivity data over cancer types, where this includes the dataset features like Cancer type, LN_ICSO, AUC, Z-score, Tissue Descriptor, Growth Properties, And Microsatellite Instabilities for enabling the predictive model and developing targeted therapy. We use tensors as a data structure for drug sensitivity prediction, using PyTorch as an open-source deep learning framework for efficient computation and manipulation of numerical data.

# Dataset Pre-Processing: 
The dataset contains information about several cancer cell lines and different drug responses. This information provides regarding compounds tested including the name of the drug, synonyms, and associated targets. This dataset includes several attributes of the cell lines used in the study namely genomic features and tumor characteristics. 
# data manipulation, data visualization, deep learning, and machine learning.
Calculate Median of LN_IC50:  the median of LN_IC50 is calculated for classifying the samples according to their sensitivity to drugs.
Categorize Drug Response: Built on the median that has been calculated, samples
are categorized into two groups:
Low Drug Sensitivity (LDS): Having low sensitivity to the drug are those whose value of cell lines with LN_IC50 is less than or equal to the median.
High Drug Sensitivity (HDS): Having high sensitivity to the drug are those whose value of cell lines with LN_IC50 is greater than or equal to the median.
Feature Selection, training, and splitting of data were done.
