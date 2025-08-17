# Death in America: Investigating death in the US

## Overview

Death in America was a research project where we were expected to choose a question/problem that they can answer using one of the predictive methods introduced in our Data Science module and report our results in a research paper. Our team chose to investigate causes of mortality in the United States through a diverse set of machine learning models, such as SVM and logistic regression, applied to a Kaggle dataset that included 2.8 million recorded deaths in the US from 2015. For my problem of interest, I explored mortalities related to motor accidents, specifically driver fatalities, due tp a 20% increase in crash deaths from 2011 to 2021. In consequence, the US faced a staggering cost of $340 billion in 2022. Thus, this highlighted how understanding the factors influencing motor accident fatalities was more critical than ever.

## Aim of Project

- **Data-Driven Insights**: Provides actionable insights for policymakers to develop effective strategies for highlighted risk groups.
- **Cost-Effective**: Offers a reliable and computationally efficient prediction model, suitable for large-scale implementation by government bodies.
- **Enhanced Safety**: Aims to reduce annual fatalities by identifying and addressing key risk factors associated with our chosen causes of mortality.

My personal aim was for the Random Forest model I employed to be able to leverage data-driven insights to inform government bodies, such as the Insurance Institute for Highway Safety (IIHS), to enhance road safety regulations, reduce fatalities, and mitigate the socioeconomic impact of road-related accidents.

## Exploring the Project

To get started with uni-ml-project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/uni-ml-project.git
   cd death-in-america
   ```
2. **Explore and Download Kaggle Dataset**:
   - Download the 2015 dataset as a csv file from Kaggle: https://www.kaggle.com/datasets/cdc/mortality/data?select=2015_data.csv
3. **Explore the Jupyter Notebooks**:
   - Within the Data_Preprocessing.ipynb file, I conducted the feature engineering and data cleaning for our group to ensure that the dataset was properly processed for our models to be trained on, which included the removal of variables containing NaN values, binarisation and filtering.
   - Within the ML_Algorithm.ipynb file, I used the preprocessed data to train my Random Forest model, where I continously evaluated and fine-tuned the hyperparameters of the model to improve the model's performance, achieving a recall of 83.4%.
4. **Full Documentation for ML Project**:
   - Access the Death_in_America.pdf to view the full project.
   - For my personal contribution to the project, turn to page 7 in the pdf document.
