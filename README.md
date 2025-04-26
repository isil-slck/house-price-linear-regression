# house-price-linear-regression

This project uses Linear Regression to predict house prices based on a variety of housing features from Ames, Iowa.
The project was completed during the Le Wagon Data Analytics Bootcamp and developed using Google Colab.

📂 Dataset
Source: Provided by Le Wagon Bootcamp

Description: Housing data from Ames, Iowa, including 75 features (e.g., lot size, year built, neighborhood).

Target Variable: SalePrice (the sale price of the house)

🛠️ Project Workflow
1. Loading the Data
Loaded the dataset into Google Colab using pandas.

2. Data Cleaning
Dropped columns with more than 30% missing values.

Imputed missing numerical values with the mean.

Imputed missing categorical values with the most frequent value (mode).

3. Feature Selection
Selected relevant features for modeling (excluding the Id column).

4. Train/Test Split
Split the dataset into training and testing sets.

5. Model Training
Built a Linear Regression model using Scikit-Learn.

6. Evaluation
Evaluated the model’s performance using  the MAE metric.

📈 Tools and Libraries
Google Colab (Python Notebook environment)

Pandas for data manipulation

NumPy for numerical operations

Scikit-Learn for modeling
