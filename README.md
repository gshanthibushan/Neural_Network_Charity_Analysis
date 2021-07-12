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
    
    *The model was not able to reach the target 75%. The accuracy for my model was 46%.*
    ![image](https://user-images.githubusercontent.com/79486450/125227412-dc15e800-e2a0-11eb-8b2f-3cd3bf6101aa.png)

  * What steps did you take to try and increase model performance?
  
    *Attempt1:  Resulted Accuracy of 72%*
    |  **Layers**  |  **Neurons**  |  **Activation functions**  |                                            
    |  :---  |  :---  |  :---  |
    |  First hidden layer  |  99  |  relu  | 
    |  Second hidden layer  |  66  |  relu  |
    |  Third hidden layer  |  33  |  relu  |
    |  Output layer  |  --  |  sigmoid  |
    
    ![image](https://user-images.githubusercontent.com/79486450/125227583-26976480-e2a1-11eb-992d-22da2cb25846.png)
    ![image](https://user-images.githubusercontent.com/79486450/125227867-ac1b1480-e2a1-11eb-9468-ff4ca4a46e58.png)

    *Attempt2:  Resulted Accuracy of 71%*
    |  **Layers**  |  **Neurons**  |  **Activation functions**  |                                            
    |  :---  |  :---  |  :---  |
    |  First hidden layer  |  100  |  relu  | 
    |  Second hidden layer  |  75  |  relu  |
    |  Third hidden layer  |  50  |  relu  |
    |  Fourth hidden layer  |  25  |  relu  |
    |  Output layer  |  --  |  selu  |
    
    ![image](https://user-images.githubusercontent.com/79486450/125228057-0d42e800-e2a2-11eb-95b0-297f92caef58.png)
    ![image](https://user-images.githubusercontent.com/79486450/125228082-1f248b00-e2a2-11eb-9a0a-7d48949c567b.png)

    *Attempt3:  Resulted Accuracy of 72%*
    |  **Layers**  |  **Neurons**  |  **Activation functions**  |                                            
    |  :---  |  :---  |  :---  |
    |  First hidden layer  |  99  |  relu  | 
    |  Second hidden layer  |  66  |  relu  |
    |  Third hidden layer  |  33  |  relu  |
    |  Output layer  |  --  |  tanh |
    
    ![image](https://user-images.githubusercontent.com/79486450/125228147-4bd8a280-e2a2-11eb-8ebf-7e507ed5acb3.png)
    ![image](https://user-images.githubusercontent.com/79486450/125228202-6874da80-e2a2-11eb-930c-e8b6b4fe5b45.png)   
    
## Summary:
