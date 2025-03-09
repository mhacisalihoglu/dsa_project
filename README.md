# DSA210 Diabetes Data Analysis Project

## Overview
This repository is created for the DSA210 project, focusing on diabetes-related data analysis. The project aims to explore trends in diabetes prevalence, patient demographics, and healthcare access using publicly available datasets.

## Dataset Information
The primary dataset used in this project is sourced from the [Data.gov Diabetes Dataset](https://catalog.data.gov/dataset/diabetes). It contains de-identified insurance data for diabetes from three managed care organizations in Allegheny County (Gateway Health Plan, Highmark Health, and UPMC) and represents their insured population for the 2015 and 2016 calendar years.

### Data Sources:
- **Diabetes 2015 Dataset** (`diabetes2015.csv`): Contains insurance claims data for diabetes patients in 2015.
- **Diabetes 2016 Dataset** (`diabetes_all_2016.csv`): Extended dataset with additional patient records from 2016.
- **NDC Codes Data** (`ndc-codes.xlsx`): National Drug Code (NDC) mapping file for identifying diabetes-related medications.

## Objectives
- Analyze the prevalence of diabetes in Allegheny County using the available insurance claim data.
- Identify trends in healthcare access, patient demographics, and treatment patterns.
- Explore potential correlations between diabetes prevalence and external factors such as socioeconomic status and healthcare coverage.
- Apply statistical and machine learning techniques to uncover hidden insights from the dataset.

## Methodology
1. **Data Cleaning & Preprocessing**
   - Handling missing values and inconsistencies.
   - Merging multiple datasets where applicable.
2. **Exploratory Data Analysis (EDA)**
   - Summarizing key statistics.
   - Visualizing distributions, trends, and correlations.
3. **Statistical Hypothesis Testing**
   - Investigating significant differences and relationships within the dataset.
4. **Machine Learning Applications** 
   - Predicting risk factors for diabetes prevalence.
   - Clustering patients based on treatment or demographic attributes.

## Repository Structure
```
/
├── data/                     # Raw and processed data files
├── notebooks/                # Jupyter Notebooks for analysis
├── scripts/                  # Python scripts for data processing
├── results/                  # Visualizations and analysis results
├── requirements.txt          # Dependencies for running the project
└── README.md                 # Project documentation (this file)
```

## Getting Started
### Installation
Clone this repository and install the necessary dependencies:
```bash
git clone https://github.com/mhacisalihoglu/dsa_project.git
cd dsa_project
pip install -r requirements.txt
```

### Running the Analysis
- Jupyter notebooks for exploratory data analysis and modeling can be found in the `notebooks/` directory.
- Python scripts for data preprocessing and visualization are stored in the `scripts/` directory.

## License
The dataset used in this project is publicly available, but users should adhere to the terms of use outlined by Data.gov.

## Contributors
- **Mehmet Ali Hacısalihoğlu**



