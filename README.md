# Auto-MPG

# Auto MPG Clustering & Dimensionality Reduction

## Project Overview
The automobile industry is undergoing major shifts due to globalization, cost pressures, and evolving customer demands. At the intersection of this transformation is the use of machine learning and data analysis to drive strategic insights and business optimization.

This project focuses on clustering and dimensionality reduction techniques to analyze vintage car data from SecondLife, a major used car dealership in the U.S. The goal is to segment cars into meaningful groups based on their technical specifications and performance characteristics, enabling the business to better target potential customers.

## Objective
The main objective of this project is to:
- Explore and understand the vintage automobile dataset.
- Apply dimensionality reduction techniques (PCA, t-SNE) to simplify and visualize high-dimensional data.
- Identify natural groupings of cars based on selected features.
- Generate business insights that can help SecondLife market vehicles more effectively.

## Dataset Description
The dataset consists of 8 variables representing various characteristics of vintage cars:

| Column | Description |
|--------|-------------|
| `mpg`  | Miles per gallon (fuel efficiency) |
| `cyl`  | Number of cylinders |
| `disp` | Engine displacement (in cubic inches) |
| `hp`   | Horsepower |
| `wt`   | Vehicle weight (in pounds) |
| `acc`  | Acceleration (time to reach 60 mph, in seconds) |
| `yr`   | Model year |
| `car name` | Name/model of the car |

## Analysis Workflow
The analysis is structured as follows:
- Exploratory Data Analysis (EDA) and correlation analysis
- Data preprocessing (standardization, missing value treatment)
- Principal Component Analysis (PCA) to reduce dimensionality
- t-SNE for nonlinear dimensionality reduction and visualization
- Clustering (K-Means, DBSCAN, etc.) to group similar vehicles
- Interpretation of clusters and actionable business insights

## Key Findings
- PCA revealed that over 90% of variance could be explained using fewer than 3 principal components.
- t-SNE visualizations showed tight clustering of vehicles based on a combination of weight, horsepower, and year.
- Clustering identified distinct groups: lightweight high-efficiency cars vs. heavier, high-performance models.
- These groupings suggest marketing opportunities to segment by eco-conscious buyers vs. performance enthusiasts.

## Tech Stack
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Notebook: Jupyter Notebook

## Project Structure
auto-mpg-clustering/
│
├── data/
│ └── auto_mpg.csv
│
├── notebooks/
│ └── auto_mpg_analysis.ipynb
│
├── images/
│ └── (optional visualizations or plots)
│
├── README.md
└── requirements.txt



## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/auto-mpg-clustering.git
   cd auto-mpg-clustering

## Install dependencies:
pip install -r requirements.txt

## Open the notebook:
jupyter notebook notebooks/auto_mpg_analysis.ipynb

## License
This project is licensed under the MIT License
