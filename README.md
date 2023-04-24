# Drug Classification using Machine-Learning techniques

This repository contains code for classifying drugs using different Machine Learning Techniques.

This project was created as part of the coursework for module 7072CEM Machine Learning for Coventry University. Any use of the code needs to be cited appropriately.

## Usage

The code can be executed in google colab - <https://colab.research.google.com/>

Make sure you upload the dataset files and specify the path for the same in the code.

Code Example:
```
# Reading the CSV file
df = pd.read_csv('/content/drug200.csv')
```

## Data

The dataset used for this project contains information on which Drug type to be prescribed to a patient based on various factors like 
- Age of the patient
- Gender of the patient
- Blood pressure levels
- Cholesterol
- Sodium to Potassium Ration in Blood

Drug type is the target variable which needs to be identified using different Machine Learning techniques.

The dataset is available here - <https://www.kaggle.com/datasets/prathamtripathi/drug-classification?datasetId=830916>

In case the link is not working you can find the dataset file under the dataset folder.

## Techniques used

As a part of this experiment, I have used three pre-defined models of classification. 
- Logistic Regression
- Decision Tree
- K Nearest Neighbor
---
## Research Paper

The paper presented as part of this experiment with all results and findings can be found in the Research_Paper folder.
