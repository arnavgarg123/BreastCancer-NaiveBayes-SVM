# BreastCancer Prediction
Analyzing various attributes on which Breast Cancer directly depends and predicting if a person with a given health conditions will have Breast Cancer.

## Motivation
Project was created to make a comparison between the accuracy of predictions obtained from Support Vector Machine and Naivebayes algorithm. The goal of the project is to tune the two algorithms in such a way that the accuracy of prediction is maximized.

## Data-set
Data-set being used in this project can be found on kaggle or you can use this [link](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) to go directly to the data-set.

## Screen shots
-HeatMap

![alt text](https://github.com/arnavgarg123/BreastCancer-NaiveBayes-SVM/blob/master/Images/heatmap.png)

-Output using NaiveBayes<br />  

| **index**  | **precision**  | **recall**  | **f1-score**  | **support**  |  
| ---  | ---  | ---  | ---  | ---  |  
|   `B`  |     0.93  |    0.95  |    0.94  |     105 |  
|     `M`   |    0.92   |   0.88  |    0.90   |     66  |  
|   **micro avg**   |    0.92   |   0.92  |    0.92    |   171|  
|   **macro avg**   |    0.92   |   0.92  |    0.92   |    171 |  
|   **weighted avg**   |    0.92  |    0.92  |    0.92  |     171 |    

-Output using SVM

| **index** | **precision** |   **recall** | **f1-score** |  **support** |
| --- | --- | --- | --- | --- |
|    `B`  |     0.94   |   0.97  |    0.95  |     105 |  
|    `M`  |     0.95  |    0.89 |     0.92  |      66 |  
|   **micro avg**   |    0.94   |   0.94  |    0.94   |    171 |  
|   **macro avg**    |   0.94    |  0.93   |   0.94    |   171 |  
| **weighted avg**     |  0.94    |  0.94 |     0.94     |  171 |  

## How to use?
### Clone
- Clone this repo to your local machine using https://github.com/arnavgarg123/BreastCancer-NaiveBayes-SVM.git
### Setup
- Make surer you have jupyter notebook installed on your system with python 3 kernel.
- Using terminal/cmd navigate to the folder containing the files of this repo and run the command `juputer-notebook`.
- Now open NaiveBayes-BreastCancer.ipynb for NaiveBayes and SVM-BreastCancer.ipynb for SVM on jupyter notebook.
 
## Contributing
### Step 1
 - Clone this repo to your local machine using https://github.com/arnavgarg123/BreastCancer-NaiveBayes-SVM.git <br />
### Step 2
 - HACK AWAY! <br />
### Step 3
 - Create a new pull request <br />

## License

[![License](https://img.shields.io/github/license/arnavgarg123/Bangladesh-Rainfall.svg?color=ye)](http://badges.mit-license.org)<br />
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/arnavgarg123/BreastCancer-NaiveBayes-SVM/blob/master/LICENSE.md) file for details
