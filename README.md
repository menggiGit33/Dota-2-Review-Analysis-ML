# Dota 2 Steam Review Classification (2024-2025)

This project focuses on building a machine learning classification model using Dota 2 Steam review data from 2024-2025. The goal is to analyze and classify reviews based on the processed dataset.

## Features

- **Data Preprocessing**: 
  - Min-Max Normalization for skewed data handling
  - RDBMS clustering for efficient data preparation
  - Feature selection to enhance the clustering process
- **Machine Learning Models**:
  - K-Nearest Neighbors (KNN)
  - Logistic Regression
- **Model Evaluation**:
  - Confusion matrix analysis
  - F1 score metrics


## Dataset

The dataset consists of 3000 [Dota 2 Steam reviews](https://steamcommunity.com/app/570/reviews/) collected between 2024-2025 for more details, it can be seen in [clustering.csv](https://github.com/menggiGit33/Dota-2-Review-Analysis-ML/blob/main/clustering.csv). Cleaned data after going through data preprocessing can be accessed in [classify.csv](https://github.com/menggiGit33/Dota-2-Review-Analysis-ML/blob/main/classify.csv) 

## Data Insight
- Skewed Data based on Dota 2 that 81% of overall review are positive
  ![image](https://github.com/user-attachments/assets/4fa952d7-1c62-4198-a5fd-37f4b2badcea)
- Correlation Between Features
  ![image](https://github.com/user-attachments/assets/3e235767-cb82-45e4-8f57-f2c579ad29c6)
- PCA projection from the RDBMS was enhanced by merging related features and removing irrelevant ones, leading to four distinct classes based on playtime and review status.
  ![image](https://github.com/user-attachments/assets/0f27152a-1739-4f62-96d8-ac87705c8a2c)



## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/menggiGit33/Dota-2-Review-Analysis-ML.git
   cd Dota-2-Review-Analysis-ML
   
