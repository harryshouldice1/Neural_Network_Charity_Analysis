# Neural_Network_Charity_Analysis

## Purpose
The goal for this challenge is to use machine learning and neural networks to help Alphabet Soup with investment predictions.
## Results:

### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?      
*If the target is noted at successful in the dataframe, it is a target for the model.

2. What variable(s) are considered to be the features for your model?    
*The IS_SUCCESSFUL column is the feature that will be considered.

3. What variable(s) are neither targets nor features, and should be removed from the input data?    
*The EIN and NAME variables don't make the model more accurate therefore they can be removed.

### Compiling, Training, and Evaluating the Model
4. How many neurons, layers, and activation functions did you select for your neural network model, and why?    
*For layer 1, 120 neurons with a relu activation.  For layer 2, 80 neurons with a relu activation.

5. Were you able to achieve the target model performance?   
*The model was able to produce 72.7%, however the target for the model was 75%.

6. What steps did you take to try and increase model performance?   
*Dropping the STATUS and SPECIAL_CONSIDERATION columns, increasing the amount of layers and neurons, using relu activation in early layers and sigmoid activation later on.
### Summary:   
The best the model could do was a 72.7% accuracy. I would recommend trying the random forest classifier because it is less affected by outliers.
