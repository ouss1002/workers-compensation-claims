# Kaggle Challenge: Workers Compensation Insurance Claims Prediction

## Description

Actuarial loss analysis [Kaggle Challenge](https://www.kaggle.com/competitions/actuarial-loss-estimation/) to predict workers compensation insurance claims

## Getting Started

### Dependencies

Found in `requirements.txt`

### Installing

* `pip install -r requirements.txt`

### Executing program

* Run `1_Preprocessing.ipynb` notebook to generate preprocessed data from raw dataset
* Run `2_Encoder.ipynb` notebook to generate embeddings for `ClaimDescription` column + `PCA` + `text_severity` 
* Run `3_XGBoost.ipynb` notebook to train the model

## Notes

* The `2_Encoder.ipynb` notebook is GPU-intensive
* The results are already uploaded with the project
* The only missing component of the project is the `./embeddings` folder