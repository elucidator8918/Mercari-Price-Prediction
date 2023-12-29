# Mercari-Price-Prediction

An explanation of the entirety of the competition can be found in this Medium Article - [Medium Read Link](https://medium.com/@forsomethingnewsid/mercari-price-suggestion-challenge-a-deep-learning-regression-case-study-5353ad1659ab)

This case study is based on the Kaggle Competition: https://www.kaggle.com/c/mercari-price-suggestion-challenge

Notebook Contents - 

|S.No  |	Section                                                 |	Jupyter Notebook                                     |
|------|----------------------------------------------------------|------------------------------------------------------|
|1.	   |Exploratory Data Analysis                                 |	EDA-CS1.ipynb                                        |
|2.	   |Data Preprocessing	& Feature Engineering                 | Feature_Engg_v6.ipynb                                |
|3.	   |Data Preprocessing	& Feature Engineering for Test data	  | Feature_Engg_TestData_v6.ipynb                       |
|4.	   |Test Model 1: Lasso                                       | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|6.		 |Test Model 2: Ridge                                       | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|7.	   |Test Model 3: ElasticNet                                  | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|8.	   |Test Model 4: SVR                                         | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|9.	   |Test Model 5: XGBoost                                     | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|10.	 |Test Model 6: LGBM                                        | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|10.	 |Test Model 7: MLP-256 with 2layers                        | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|10.	 |Test Model 8: MLP-1024 with 6layers                       | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|11.	 |Final Ensemble Model of MLP-256 and MLP-1024              | BaselineModelFinal_v4_BEST(BN+RELU).ipynb            |
|12.	 |Final Pipeline Function 1 - Prediction Output             | Final_Submission_Case_Study1.ipynb                   |
|13.	 |Final Pipeline Function 2 - RMSLE Metric Output           | Final_Submission_Case_Study1.ipynb                   |

Final Loss Table - 

|             Model              |                Features used                | CV Loss = RMSLE |
|--------------------------------|---------------------------------------------|-----------------|
|        Lasso Regression        | TF-IDF + Feature Combined for name and text |      0.745      |
|        Ridge Regression        | TF-IDF + Feature Combined for name and text |      0.444      |
|          Elastic Net           | TF-IDF + Feature Combined for name and text |      0.745      |
|              SVR               | TF-IDF + Feature Combined for name and text |      0.687      |
|            XGBoost             | TF-IDF + Feature Combined for name and text |      0.450      |
|              LGBM              | TF-IDF + Feature Combined for name and text |      0.439      |
|         MLP Model - 256        | TF-IDF + Feature Combined for name and text |      0.420      |
|         MLP Model - 1024       | TF-IDF + Feature Combined for name and text |      0.412      |
| Ensemble Model (MLP-256 + MLP-1024) | TF-IDF + Feature Combined for name and text |      0.4047|
