Weather Data Clustering Analysis
Overview

This project explores clustering techniques applied to weather data using Python and Jupyter Notebook.

The project includes data preparation and preprocessing steps required before performing clustering analysis. In particular, the notebook works with sampling and data-cleaning operations to prepare the dataset for further analysis.

Project Objectives
Prepare weather data for analysis
Create a representative sample of the dataset
Clean and preprocess the data
Handle missing values
Remove columns that are not required for the analysis
Prepare the cleaned dataset for clustering
Data Preparation

The data-cleaning process includes:

Removing the rain_accumulation column
Removing the rain_duration column
Removing rows containing NULL/missing values
Creating a copy of the original DataFrame so the original data is not modified

The notebook also includes a down-sampling step to work with a smaller subset of the data.

Technologies Used
Python
Jupyter Notebook
NumPy
Pandas
Data preprocessing and clustering techniques
Repository Structure
.
├── Clustering Exercise Notebook - SOLUTIONS.ipynb
└── README.md
Getting Started
1. Clone the repository
git clone <your-repository-url>
cd <repository-name>
2. Install the required libraries
pip install pandas numpy jupyter
3. Start Jupyter Notebook
jupyter notebook

Open the clustering notebook and run the cells from top to bottom.
