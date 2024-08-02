# Movies-Analyze-Project
## Overview
This is a project to practice my Python skills by cleaning the dataset and analyzing it by using visualization. It aims to find the top 10 movies in the year with the highest average movies rating.
## Tools & Librarys
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
## Dataset
The dataset that I used in this project is from Kaggle: MOVIES DATASET FOR FEATURE EXTRACION ,PREDICTION
https://www.kaggle.com/datasets/bharatnatrayn/movies-dataset-for-feature-extracion-prediction/code
## Steps in project
### 1.Import and cleaning data
- Drop column Gross that mostly data are missing values.
- Drop all rows with missing values.
- Convert data types.
- Clean text data.
- Extracting Director from Stars column.
- Extracting Start-Year and End-Year from Year column.
### 2.Analysis
- Distribution of rating
- Correlation heatmap
- Trend of Total Movies
- Average Movie Rating Per years
- Top 10 Movies
### 3.Summmary insights
- Most movie rating are in 6-8.
- Year with highest average movies rating are in 2018
- Top 10 Movies in 2018 are:
  - Naui Ajusshi
  - My next guest needs no introduction with david letterman
  - Yeh Meri Family
  - Velhas Amigas
  - Pose
  - Car Masters: Rust to Riches
  - College Romance
  - Miseuteo Shunshain
  - One Strange Rock
  - SKY Castle

> [!NOTE]
> The result in this project might incorrect due to dropping lots of data from missing values.
