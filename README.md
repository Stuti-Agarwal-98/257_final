# nlp-1
# Team - BTS ( Bharath gunasekaran, Tamanna Mehta and Stuti Agarwal)
## spring 2021 sjsu final exam problem set
# Datasets

## Dataset - 1 : Politifact dataset: Scraped from Poltifact.com
## Dataset - 2 : Snopes dataset: Scraped from Snopes.com
## Dataset - 3 : Amalagamted Dataset - 1 & Dataset - 2
## Inference Dataset: NewsAPI

# ipynb Files and tasks performed:
## 00_data-prep.ipynb: 

### Scrape latest Politifact.com with 17682 records , Scrape latest Snopes.com with 7022 records, 
### Pulled Inference data from NewsAPI. Done inference using a Button , loaded all the models (sklearn, bert and keras) and ran inference .

## 01_sklearn-embedding-pipelines.ipynb: 

### Loaded Dataset - 1 , trained the model on it, saved the model, saved the prediction,
### saved the y_test values, Loaded Dataset - 2 ,trained the model on it, saved the model,
### saved the prediction, saved the y_test values, Amalgamated_Dataset - 1 and Dataset - 2 ,
### trained the model on it, saved the model, saved the prediction, saved the y_test values,
### mapped the label to the 1-6 labels, Did evaluation and comparison using the same ROC visualization as 004_comparison Colab
### Comparison of model roc scores across datasets for sklearn:

![image](https://user-images.githubusercontent.com/71077352/119454317-47096080-bced-11eb-8b8f-c1ac25d0fecf.png)


## 02_keras.ipynb:

### Replaced FastText embeddings with Glove ,Loaded Dataset - 1 , trained the model on it,
### saved the model, saved the prediction, saved the y_test values, Loaded Dataset - 2 ,
### trained the model on it, saved the model, saved the prediction, saved the y_test values,
### Amalgamated_Dataset - 1 and Dataset - 2 , trained the model on it, saved the model, saved the prediction,
### saved the y_test values,mapped the label to the 1-6 labels, Did evaluation and comparison using the same ROC visualization as 004_comparison Colab
### Comparison of model roc scores across datasets for keras:

![image](https://user-images.githubusercontent.com/71077352/119454547-8041d080-bced-11eb-9474-9d5d1fb743c9.png)


## 03_bert.ipynb :

### Loaded Dataset - 1 , trained the model on it, saved the model, saved the prediction, 
### saved the y_test values, Loaded Dataset - 2 ,trained the model on it, saved the model,
### saved the prediction, saved the y_test values, Amalgamated_Dataset - 1 and Dataset - 2 ,
### trained the model on it, saved the model, saved the prediction, saved the y_test values,
### mapped the label to the 1-6 labels, Did evaluation and comparison using the same ROC visualization as 004_comparison Colab
### Comparison of model roc scores across datasets for bert:

![image](https://user-images.githubusercontent.com/71077352/119454814-ce56d400-bced-11eb-8b40-df598670102c.png)


## 04_ compare-experiments.ipynb:

### Loaded the predictions and y_tests for each model for sklearn, bert and keras and
### calculated the RUC scores and compared the sklearn,bert,keras models across Dataset - 1, Dataset - 2 and Amalgamated dataset .

# Comparison across all three for dataset - 1(politifact)

![image](https://user-images.githubusercontent.com/71077352/119452563-5d162180-bceb-11eb-9215-27725bb6fc24.png)


# Comparison across all three for dataset - 2(Snopes.com)

![image](https://user-images.githubusercontent.com/71077352/119452682-78812c80-bceb-11eb-9065-fad3bf39f613.png)

# Comparison across all three for Amalgamated Dataset

![image](https://user-images.githubusercontent.com/71077352/119452775-977fbe80-bceb-11eb-8231-cde86eebd737.png)

# Team Contributions:

## 00_data-prep.ipynb: Data Scraping: Bharath & Stuti, Inference : All
## 01_sklearn-embedding-pipelines.ipynb : Bharath Gunasekaran
## 02_keras.ipynb : Tamanna Mehta
## 03_bert.ipynb : Stuti Agarwal
## 04_ compare-experiments.ipynb : All






