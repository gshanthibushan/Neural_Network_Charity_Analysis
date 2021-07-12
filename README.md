# Neural_Network_Charity_Analysis
Neural Networks and Deep Learning Models

## Overview of the analysis:
For this analysis, created a six different supervised machine learning models that could predict credit risks. Following models were used to predict the credit risk.

 * Naive Random Oversampling
 * SMOTE Oversampling
 * Cluster Centroid Undersampling
 * SMOTEENN Sampling
 * Balanced Random Forest Classifying
 * Easy Ensemble Classifying

## Results:
### Data Preprocessing
  * What variable(s) are considered the target(s) for your model?
  
    *The follwing variable is considered as target of the model: IS_SUCCESSFUL.*
  ![image](https://user-images.githubusercontent.com/79486450/125225347-27c69280-e29d-11eb-8dfa-ac6261ff4205.png)

  * What variable(s) are considered to be the features for your model?

    *The following variables are considered as the features of the model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.*

  * What variable(s) are neither targets nor features, and should be removed from the input data?

    *The following variables are not considered as target nor features and it has been removed from the input data: EIN & NAME.*
   ![image](https://user-images.githubusercontent.com/79486450/125226294-cbfd0900-e29e-11eb-9d1e-77434114cc50.png)

### Compiling, Training, and Evaluating the Model
  * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    Model: "sequential"
    |  **Layers**  |  **Neurons**  |  **Activation functions**  |                                            
    |  :---  |  :---  |  :---  |
    |  First hidden layer  |  80  |  relu  | 
    |  Second hidden layer  |  30  |  relu  |   
    |  Output layer  |  --  |  sigmoid  |
    
    ![image](https://user-images.githubusercontent.com/79486450/125226453-1ed6c080-e29f-11eb-9330-f2941e584e91.png)

  * Were you able to achieve the target model performance?
    
    *The model was not able to reach the target 75%. The accuracy for my model was 46%.
    ![image](https://user-images.githubusercontent.com/79486450/125227412-dc15e800-e2a0-11eb-8b2f-3cd3bf6101aa.png)

  * What steps did you take to try and increase model performance?
  
    |  **Layers**  |  **Neurons**  |  **Activation functions**  |                                            
    |  :---  |  :---  |  :---  |
    |  First hidden layer  |  80  |  relu  | 
    |  Second hidden layer  |  30  |  relu  |   
    |  Output layer  |  --  |  sigmoid  |
    
    
## Summary:
