## Project Summary
This is an exploratory project for the Stroke Prediction Dataset found at Kaggle. Details of the dataset can be found at this [link](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

## Methodology
One hot encoding was done on the categorical variables before fitting them into a logistic regression to predict the probability of having a stroke. The log

<img src="https://latex.codecogs.com/svg.latex?\Large&space;Pr(Y_i=1|X_i) = {\frac{\exp(\beta_0 + \beta_1X_i + \beta_2X_2 + \beta_3X_3 + \beta_4X_4 + \beta_5X_5)}{1 + exp (\beta_0 + \beta_1X_i + \beta_2X_2 + \beta_3X_3 + \beta_4X_4 + \beta_5X_5)}}" />

## Built With
The files included in this repository are written using **Google Collab**. Google Collab is a Google research project created to help disseminate machine learning education and research. It's a Jupyter notebook environment that requires no setup to use and runs entirely in the cloud. 

## File Structure
* ```healthcare-dataset-stroke-data.csv```: Stroke Prediction Dataset found at Kaggle
* ```Stroke Prediction.ipynb```: Source code for Stroke Prediction.

## Running the project for evaluation
1. Clone the repository.
```
$ git clone https://github.com/Joeltzy/Stroke-Prediction/.git
```
2. Open the file `Stroke Prediction.ipynb` in a Jupyter Notebook or Google Collab. 
