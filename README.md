# Yelp Dataset Challenges
This repository contains the codes for 3 projects on the Yelp Dataset for a Deep Learning course in HKUST

The training method for each project is provided under `Final_model.ipynb` in each folder, as well as the training and validation data used. 

The report `Project_report.pdf` for each project will further discuss the model and features of the data used, as well as further explain the implementation and the final hyperparameters.
<br><br>

## Projects

[Project 1](https://github.com/VanHoann/Yelp_Dataset_Challenges/tree/main/Sentiment_Analysis): Sentiment Analysis, predicting the rating based on the user reviews, here only the text review is used. The final model uses the Transformers-based [RoBERTa](https://arxiv.org/abs/1907.11692) model, which is able to achieve **70.60%** validation accuracy and **0.6648** Macro-F1 score
<br>

[Project 2](https://github.com/VanHoann/Yelp_Dataset_Challenges/tree/main/Link_Prediction): Link Prediction using [GraphSAGE](https://arxiv.org/abs/1706.02216), predicting the presence of relationship between vertices using DFS-like approach. The final model uses AUC score metrics, and able to achieve **95.76%**
<br>

[Project 3](https://github.com/VanHoann/Yelp_Dataset_Challenges/tree/main/Recommendation_Prediction): Recommendation Prediction based on [Neural Collaborative Filtering](https://arxiv.org/abs/1708.05031) implementation with some feature engineering. RMSE metrics is used, and the final model is able to achieve the value of **1.061**
> Another competitive approach is [Wide and Deep Learning](https://arxiv.org/abs/1606.07792)
<br>

## Training Environment

All of the training of the model is done on [Google Colab](https://colab.research.google.com/) because of their GPU support, which is free and requires no installations.
<br><br>

## Useful links

* Download the dataset: https://www.yelp.com/dataset
* Data documentation: https://www.yelp.com/dataset/documentation/main
* Past winners and their papers: https://www.yelp.com/dataset/challenge/winners
