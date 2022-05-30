# Data Science Assignment (Binary Classifcation)
## Arunava Kumar Chakraborty


### Introduction:

In this assignment, the machine learning-based approach for binary classification has been presented. In order to execute the analysis, the following datasets have been used - 
- **training_set.csv** - Contains 3910 records, 57 features, 1 output
- **test_set.csv** (without Ground Truth) - Contains 691 records, 57 features

In this experiment, the datasets will be per-processed to clean the noise. Then the relevant features will be executed based on the linear relationships between them. Different baseline machine learning models will be developed to perform the classification task based on the selected features. Finally, the best-performing model will be selected to predict the target value for the test dataset by analyzing the feature set.


### Workflow of the Project:

    i. Data Preprocessing
       a. Rename the unnamed column
       b. Missing Values Removal
       c. Outliers Removal

        ii. Feature Extraction
            a. Correlation Analysis [Train Data]
            b. Feature Selection
    
            iii. Predictive Analysis
                 a. Train-Val-Test Split
                 b. Classification Models
                    - Logistic Regression Model
                    - KNN Classification Model
                    - Decision Tree Regression Model
                    - AdaBoost Regression Model
                    - Random Forest Classification Model
                    

### Analysis:
During the analysis, it has been found that the **Random Forest** classifier outperforms all other machine learning classifiers and achieved **94.48%** validation accuracy for binary classification on the validation dataset. So the **Y** values of the test dataset will be predicted using **Random Forest** classifier for future analysis.


### Future Scope

In the future, the feature selection method can be improved for better performance of these machine learning models. In order to achieve better classification accuracy, these machine learning models can be improved by finding the best parameters during the training phase.


#### - By Arunava Kumar Chakraborty
