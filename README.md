# Ecommerce-Simulation-Dataset
This project is dedicated to generating a high-fidelity simulated dataset for an ecommerce platform specializing in computers and video games. The dataset aims to mirror real-world transactional data, providing a robust foundation for analytics, machine learning models, and data architecture simulation.

## Overview
The dataset encompasses a variety of features, including:

Transactional data for computer and video game purchases
Customer interaction data with various touchpoints (organic, paid, and influencer-driven)
Simulated financials, such as pricing, commissions, and revenue
Geographic distribution of sales across major cities
Multiple payment method scenarios
Order statuses reflecting a realistic customer journey
This data is invaluable for:

Data analysts and scientists looking to practice data wrangling, exploration, and visualization
Data engineers who need to architect data pipelines and storage solutions
Machine learning practitioners requiring transactional data for predictive modeling
Ecommerce strategists analyzing market trends and consumer behavior

```css
/dataset-simulator
│
├── /data
│   ├── raw_data/               # Folder for unprocessed data
│   └── processed_data/         # Folder for processed data
│
├── /notebooks
│   ├── data_exploration.ipynb  # Jupyter notebooks for data exploration
│   └── data_generation.ipynb   # Jupyter notebooks for data generation
│
├── /scripts
│   ├── generate_data.py        # Scripts to generate the dataset
│   └── preprocess_data.py      # Scripts to preprocess the data
│
├── /tests
│   ├── test_data_quality.py    # Tests to ensure data quality
│   └── test_generation.py      # Tests for data generation scripts
│
├── .gitignore                  # Files and folders to be ignored by git
├── LICENSE                     # Repository's license
├── README.md                   # Project information, how to use it, contribute, etc.
└── requirements.txt            # Dependencies needed to reproduce the environment

```
