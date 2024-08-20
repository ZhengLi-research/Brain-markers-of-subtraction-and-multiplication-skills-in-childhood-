# Brain markers of subtraction and multiplication skills in childhood: task-based functional connectivity and individualized structural similarity

## Overview
To identify the brain markers for subtraction and multiplication skills in childhood, the present study used a data-driven connectome-based prediction model to identify brain markers of arithmetic skills from arithmetic-state functional connectivity (FC) and individualized structural similarity (SS) in 132 children aged 8-15 years. 

To ensure reproducibility of experimental results, we provide neuroimage data and behavioral data used to predict children's arithmetic ability. These data have been preprocessed.

## Raw data introduction
The raw data for our study were obtained from a longitudinal neuroimaging dataset entitled “Brain Correlates of Math Development”, which is publicly available in OpenNeuro (https://openneuro.org/datasets/ds001486/versions/1.3.0). A detailed description of this dataset can be found in a previous study by Suárez-Pellicioni et al. (2019). In this dataset, a total of 132 typically developing children aged 8-15 years received functional and structural MRI scanning and completed both subtraction and multiplication tasks. 

## preprocessed data introduction

To ensure the reproducibility of our experimental findings, we have made available preprocessed data on task-state functional connectivity and structural similarity connectivity, along with the behavioral data that have been adjusted for covariates.

We conducted an assessment of the cognitive behavioral capabilities of our subjects, taking into account factors such as psychiatric status, literacy skills, and intelligence quotient (IQ). Additionally, we evaluated the integrity of their brain structural data. Following this comprehensive evaluation, a total of 121 subjects were selected for the analysis of structurally similar connections, which we refer to as the "Structurally Similar Connectome Group."

Subsequently, we performed a further evaluation of these subjects. After implementing quality control measures on the brain function data, we identified 95 subjects whose data met our criteria for the calculation of functional connections, which we designate as the "Functional Connectome Group."

### NeuroImageData:
- SubtractionStateFunctionalConnectivityData.zip: subtraction state function connection data (functional connectome group)
- MultiplicationStateFunctionalConnectivityData.zip: multiplication state function connection data (functional connectome group)
- StructuralSimilarityData.zip: structurally similar connection data (structurally similar connectome group)

### ArithmeticBehaviorData: 
This file contains the behavioral data utilized for the training of predictive models. These data have been adjusted for covariates. For the functional connectome, the variables considered in the regression analysis were age, gender, head movement, and intelligence. In the case of the structural connectome, the variables subjected to regression included age, gender, Total Intracranial Volume (TIV), and intelligence.

- SubtractionCMATScoreforFunctionalConnectivity: children's subtraction arithmetic ability behavioral data (functional connectome group)
- SubtractionCMATScoreforStructuralSimilarity: subtraction arithmetic ability behavioral data (structurally similar connectome group)
- MultiplicationCMATScoreforFunctionalConnectivity: multiplicative arithmetic ability behavioral indicators (structurally similar connectome group)
- MultiplicationCMATScoreforStructuralSimilarity: multiplicative arithmetic ability behavioral indicators (structurally similar connectome group)

### covariance.xlsx: 
- This file provides covariate data for regression of behavioral data


