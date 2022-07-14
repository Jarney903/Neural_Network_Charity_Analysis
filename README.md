# Neural_Network_Charity_Analysis
Module #19


## Project Overview
With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup

## Resources
- Data Source: charity_data.csv
- Software: Python 3.7, google colab, sklearn library, pandas, tensorflow


## Analysis Results
### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL
What variable(s) are considered to be the features for your model?
- All others other than target and dropped columns
What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and NAME

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Hidden Layer #1: 100 neurons, relu
- Hidden Layer #2: 50 nerons, relu
- Output Layer #3: sigmoid
Were you able to achieve the target model performance?
- No, I achieved 57% accuracy
![1](https://github.com/Jarney903/Neural_Network_Charity_Analysis/blob/main/analysis/Fig_1.jpg)
What steps did you take to try and increase model performance?
- Step #1: Dropped "USE_CASE" column 
- Step #2: Increased Hidden Layers to 3 and Nodes to 100, 80, and 70 respectivley 
- Step #3: Changed output layer to relu
![2](https://github.com/Jarney903/Neural_Network_Charity_Analysis/blob/main/analysis/Fig_2.jpg)


## Analysis Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
- The overall results for the 3 optimizations attempts were ultimately unsuccessful. The accuracy decreased from 57% to 53%. I would attempt to use other supervised methods such as Support Vector Machines or Random Forest to try solving this problem, as these my be better at not linear grouping. 
![2](https://github.com/Jarney903/Neural_Network_Charity_Analysis/blob/main/analysis/Fig_3.jpg)

