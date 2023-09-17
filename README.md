## Heart_Failure_Prediction
### About The Data:
- Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.
- People with cardiovascular disease or who are at high cardiovascular risk (due to one or more risk factors such as hypertension, diabetes, hyperlipidemia, or already established disease) need early detection and management wherein a machine learning model can be of great help.



### This is the workflow of how the data is being used through the building of the model:
- the training dataset is used to train a few candidate models
- validation dataset is used to evaluate the candidate models
- one of the candidates is chosen
- the chosen model is trained with a new training dataset
- the trained model is evaluated with the test dataset

### The models I used:
- RandomForestClassifier
- AdaBoostClassifier
- GradientBoostingClassifier
- XGBClassifier




  * You can check the dataset from here:  https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction
  * You can check my notebook in the Kaggle from here:  https://www.kaggle.com/code/shawkyelgendy/model-selection-workflow-using-cross-validation
