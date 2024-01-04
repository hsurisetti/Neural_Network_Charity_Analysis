# Neural Network Charity Analysis

## Overview of the Analysis:
The purpose of this analysis is to create a deep learning neural network model that can accurately predict which charitable organizations are worth donating to. To achieve this, we used a dataset provided by AlphabetSoup, containing over 34,000 organizations that have received funding from AlphabetSoup over the years.

## Results:

### Deliverable 1 Results :

<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.1.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.2.png" width=410 />

<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.3.png" width=380 /><img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.4.png" width=380 /><img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.5.png" width=380 /><img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.6.png" width=380 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.7.png" width=380 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.8.png" width=380 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.9.png" width=380 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.10.png" width=380 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/11.png" width=380 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.12.png" width=380 />

### Deliverable 2 Results :

<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/2.1.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/1.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/2.3.png" width=380 />

### Deliverable 3 Results :

<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/3.1.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/2.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/3.3.png" width=380 />


<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/3.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/4.2.png" width=410 />

<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/4.png" width=410 />
<img src="https://github.com/hsurisetti/Neural_Network_Charity_Analysis/blob/main/screenshots/5.2.png" width=410 />

## Data Preprocessing:

- ### What variable(s) are considered the target(s) for your model?

The target variable for the model is the "IS_SUCCESSFUL" column, which indicates whether or not the funding was successful.

- ### What variable(s) are considered to be the features for your model?

The features used for the model are "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", and "SPECIAL_CONSIDERATIONS".

- ### What variable(s) are neither targets nor features, and should be removed from the input data?

The "EIN" and "NAME" columns were neither targets nor features and were removed from the input data.

## Compiling, Training, and Evaluating the Model:

- ### How many neurons, layers, and activation functions did you select for your neural network model, and why?

For the optimized neural network model, I selected 80 neurons for each of the three hidden layers, using the "tanh" activation function. The input layer has a number of neurons equal to the number of features, which was 43 for the final model. The output layer has a single neuron and uses the "sigmoid" activation function to output the probability of the target variable being equal to 1.

- ### Were you able to achieve the target model performance?

No, I got closer to the target model performance of 75% accuracy but were not able to reach fully. The optimized model achieved an accuracy of 72.20% and a loss of 0.5637.

- ### What steps did you take to try and increase model performance?

To increase model performance, I experimented with different numbers of neurons in the hidden layers, various activation functions, and additional hidden layers. I also tried different optimization algorithms, batch sizes, and epochs.

## Summary:

Overall, deep learning neural network model was able to achieve an accuracy of around 0.72 on the test data. While this is a decent performance, I can still try to improve it further by using different models. One recommendation could be to use a Random Forest model. This model is robust, fast and has good accuracy. Another option is to use an XGBoost classifier model, which is known for its high accuracy and handling complex datasets. Further optimization for this neural network model can be done by further adjusting the learning rate, adding regularization techniques, or using different optimization algorithms.
