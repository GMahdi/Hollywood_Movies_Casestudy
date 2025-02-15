# Hollywood Blockbuster Movies Case Study

## Project Overview

This project aims to develop a machine learning model to predict the gross revenue category of Hollywood movies based on various features such as production budget, genre, creative type, release pattern, and more.

The project follows a structured data pipeline, including exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Dataset Details

The project includes two datasets:
### 1. Training Dataset

Used to train the model, it contains:

    Movie metadata (e.g., name, production year, genre, language)
    Production details (e.g., sequel status, creative type, source)
    Financial data (e.g., total gross earnings)
    Categorical label (based on total earnings)

### 2. Scoring Dataset

Used for model predictions, it includes similar features except:

    It contains "production_budget" instead of "total".
    The model must predict the revenue category based on given features.

## Files Included

    📂 Movie_ratings_Casestudy.ipynb → Jupyter Notebook containing EDA, feature engineering, model training, and evaluation
    📂 ScoringSheet.csv → Contains predicted categories for the scoring dataset
    📂 README.md → This document
    📂 Training sheet.xlsx → Training Data

## Methodology

    Data Exploration & Cleaning
        Handled missing values and inconsistencies
        Explored correlations between features and revenue

    Feature Engineering
        Converted categorical variables using encoding techniques
        Extracted insights from text features (e.g., board_rating_reason)
        Used TF-IDF for text processing

    Model Training & Evaluation
        Used XGBoost and other ML models for classification
        Evaluated using accuracy, confusion matrix, and F1-score

    Predictions & Output Generation
        Applied the trained model to scoring data
        Saved predicted categories in ScoringSheet.csv

## Key Considerations

    No web scraping is used in the primary model (as per guidelines)
    Feature selection is done carefully to optimize accuracy
    Both accuracy and methodology are considered for evaluation

## How to Run the Notebook

1️⃣ Install dependencies:

pip install -r requirements.txt

2️⃣ Open the Jupyter Notebook:

jupyter notebook Movie_ratings_Casestudy.ipynb

3️⃣ Run all cells to train the model and generate predictions

## Results & Insights

    Key drivers of revenue include production budget, genre, and release pattern
    Text-based features like board rating reason provided additional predictive power
    The final model achieved high accuracy in predicting revenue categories

## Future Improvements

✅ Incorporating additional data sources (e.g., actors, director influence)
✅ Using deep learning models for enhanced text processing
✅ Improving feature selection and hyperparameter tuning
Contact

For any queries, please reach out to [ghulam.mahdi@gmail.com]

This README provides a professional and structured overview of your project. Let me know if you'd like any modifications! 🚀
