# cs171_customer_churn_prediction
Official repo for the final project of CS171. We will be using the Telco customer churn: IBM dataset from Kaggle to predict whether a given customer will churn using Logistic Regression.  

## Project Title: Customer Churn Prediction with Logistic Regression ##

## Authors ##
- Nyi Wai Yan Tun

## Description of Question and Research Topic ##
- For this project, we will be using Telco customer churn: IBM dataset from Kaggle. This dataset has about 7000 rows of data and 33 columns which ranges from detailed customer demographics to service infromation and billing information. The question for this project is to predict the likelihood of customer churn using customer's demographics and available member information. We will be using Logistic Regression to evaluate which customers are likely to churn or to stay. This project will leverage data and Machine Learning to tackle customer retention which is a common real world problem.

## Data Collection ##
- Downloading Dataset from Kaggle; IBM Telco Customer Churn Dataset
- Cleaning and Preprocessing to handle missing values and encode categorical values

## Model Plan ##
- Will build and test a Logistic Regression model to predict customer churn. This includes training the model and checking how well it performs using accuracy, precision, recall, F1-score and ROC-AUC. This model will also analyze feature coefficients to identify key factors that influence churn behavior. 

## Project Timeline ##
Week 1: Data collection, cleaning, and preprocessing
Week 2: Exploratory data analysis and visualization
Week 3: Model building and evaluation
Week 4: Interpret results and finalize report

To run this project locally, first clone the repository and install all required dependencies:
## Installation Instructions ##
```bash
git clone https://github.com/Nyiwyt/cs171_customer_churn_prediction.git
cd cs171_customer_churn_prediction
pip install -r requirements.txt


## Project Structure ##
cs171_customer_churn_prediction/
│
├── data/                        # Raw dataset (not tracked by git)
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── analysis_visualization.ipynb
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore## Data Access Statement ##

The dataset used for this project is the IBM Telco Customer Churn dataset hosted on Kaggle:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Due to Kaggle licensing restrictions, the dataset is not included in this repository. Users must manually download the dataset and place it in the following directory:

data/WA_Fn-UseC_-Telco-Customer-Churn.csv


## How to Run the Project ##
To run the project, download the dataset from kaggle and place it in the data/ folder
Next, install the required packages using:

pip install -r requirements.txt

Run the following notebooks in top down order
1. data_preprocessing.ipynb
2. model_training.ipynb
3. analysis_visualization.ipynb

## Reproducibility ##

This project is fully reproducible across different operating systems (Windows, macOS, Linux). All file paths are relative, and all required Python packages are listed in requirements.txt. Random seeds are fixed during model training to ensure consistent results.

To reproduce the results, install the dependencies and run all notebooks from top to bottom in the specified order.


## Results Summary ##

The Logistic Regression model achieved strong predictive performance for customer churn classification. Model evaluation included accuracy, ROC-AUC score, and confusion matrix analysis. Feature coefficient analysis was used to identify the most influential factors contributing to churn behavior

## Future Work ##

If this project were to be extended, future improvements could include:

1. Testing additional machine learning models such as Random Forest and XGBoost
2. Applying dimensionality reduction techniques such as PCA
3. Exploring deep learning approaches using PyTorch

## Project Roles ##

Nyi Wai Yan Tun: Data collection, preprocessing, model development, model evaluation, visualization, documentation, and project coordination.



