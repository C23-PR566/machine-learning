# Machine Learning Path Repository
This repository is for completing the Product Capstone Project by Bangkit Academy 2023: Machine Learning Path

## Workflow
Data Collection  ➡️ Data Preprocessing ➡️  Model Creation ➡️ Model Conversion (TF Lite) ➡️ Model Deployment

## Data Collection

We compiled BISINDO dataset from Kaggle and also create our own dataset to train the model.
These are the links to the Kaggle dataset that we have used to train the model.
* [Dataset 1 (Kaggle)](https://www.kaggle.com/datasets/achmadnoer/alfabet-bisindo)
* [Dataset 2 (Kaggle)](https://www.kaggle.com/datasets/riestiyazain/bisindo2)
* [Dataset 3 (Kaggle)](https://www.kaggle.com/datasets/alfredolorentiars/bisindo-letter-dataset)
* [Dataset 4 (Kaggle)](https://www.kaggle.com/datasets/idhamozi/indonesian-sign-language-bisindo)
* [Dataset 5 (Our own manually created dataset)](https://drive.google.com/file/d/1tRZBQE3qGpLg6KT5KJhulEy9lAzlao0O/view)
* [Final Dataset (Compiled & preprocessed)](https://drive.google.com/file/d/1umtKaYyuJG48eDvGSDnrOBwfg6E5mkPB/view?usp=sharing)

## Data Preprocessing

In this step, we try to remove pictures that are extremely augmented, and also pictures that contains a face in it. Those type of pictures are quite affecting the performance of our model (known after several trial and error).

## Model Creation

In this step, we try to create a model from scratch and also a model that use transfer learning (MobileNet_V2). After several trial and error, we found that the model with transfer learning performs much better, and we decided to use it as a final model.

## Model Conversion

In this step, we use the default optimizations method to do the model conversion.

## Model Deployment

The model is deployed on the Android app and will be used in the "Kuis" feature to classify the picture taken by the user.
