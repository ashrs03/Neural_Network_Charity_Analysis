# Neural_Network_Charity_Analysis

## Purpose 

Beks received a CSV containing more than 34,000 organizations from the Alphabet Soup's business team that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization. The objective is to preprocess this data for neural network model and train, evuluate and optimize the model. By creating binary classifier, the model is to predict if the organization desiring funds will be successful if funded by Alphabet Soup and this will be based on features in the dataset. 

Number of inputs are to be determined, and also neurons and layers in the model. Once model is at state, the goal is to compile train and evuluate binary classification model to calculate the model's loss and accuracy. 

 
## Results

Data Preprocessing
What variable(s) are considered the target(s) for your model?

IS_SUCCESSFUL column is the target for the model

What variable(s) are considered to be the features for your model?

The remaining columns are the features for the model.

What variable(s) are neither targets nor features, and should be removed from the input data?

'EIN' and 'NAME' are not beneficial and are neither targets nor features and were removed from input data. 

Unique values in each column after the specified columns are removed ( Is_Successful of these columns is the target and rest are features)

![image](https://user-images.githubusercontent.com/42523379/216233822-94bdcca4-b847-4d6f-9f6b-6b3f02a98190.png)

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Below shows the selection of neurons, layers and activation function. The relu and sigmoid activation seemed to fit better for layer 3 and layer 4

![image](https://user-images.githubusercontent.com/42523379/216239070-986dc365-757a-4abe-b8f1-e84408aa147f.png)

Were you able to achieve the target model performance?

The model was able to gain accuracy of 72.6% and fell short of the target of 75%

![image](https://user-images.githubusercontent.com/42523379/216238600-4653e637-48ac-4d75-9e56-991eb75e7768.png)

What steps did you take to try and increase model performance?

Columns were reviewed and the STATUS and SPECIAL_CONSIDERATIONS columns were dropped as well as increasing the number of neurons and layers. 
Relu activiation in first couple layers and sigmoid in last fetched better results. 

## Summary 
The relu and sigmoid activations resulted in 72.6% accuracy, and using various number of neurons and layers this was max achieved. 
The next step can be to try the random forest classifier as it is supposed to be less influenced by outliers.
