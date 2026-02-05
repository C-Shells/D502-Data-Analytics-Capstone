# COVID-Era Changes in U.S. Human Trafficking  
## Analyzing COVID-Era Shifts in U.S. Human Trafficking Through Advanced Analytical Methods  

This repository contains the code, data preparation steps, statistical tests, and machine learning models used to analyze how documented human trafficking patterns in the United States changed before and after the onset of the COVID‑19 pandemic. The project includes chi‑square tests, PCA dimensionality reduction, k‑means clustering, and visualizations that support the final written analysis.  

## Project Structure  
- **/data_files/** Contains the CTDC synthetic dataset (not included in repository if restricted).  
- **/notebooks/** Jupyter Notebook with all code, analysis steps, and visualizations.  
- **/analysis/** Supporting visuals and exported figures.  
- **README.md** Project overview, environment setup, and instructions.  

## Project Overview  
This project evaluates whether patterns of human trafficking changed in the United States after COVID‑19. The analysis focuses on:  
- Type of exploitation  
- Means of control  
- Relationship to exploiter  
- Pre‑ vs. post‑COVID distributions  
- Dimensionality patterns (PCA)  
- Natural groupings (k‑means clustering)  

The goal is to determine whether statistically significant shifts occurred and whether machine learning models support or contrast with chi‑square findings.  

## Environment & Tools  
This project was developed in:  
- **Windows 10**  
- **WSL (Ubuntu)**  
- **VS Code**  
- **Jupyter Notebook**  

## Required Libraries  
The libraries used in this project include:  
- pandas  
- numpy  
- scipy  
- scikit‑learn  
- matplotlib  
- seaborn  
- jupyter  

## Data Source  
The dataset was obtained from the Counter-Trafficking Data Collaborative (CTDC) on January 2, 2026  
https://www.ctdatacollaborative.org/page/global-synthetic-dataset  


## Data Preparation Summary  
Key Preparation steps include:  
- Filtering to U.S. cases  
- Handling missingness  
- Converting datatypes  
- Creating pre-/post‑COVID helper column  
- One‑hot encoding categorical variables  
- Scaling features for PCA  
- Reducing dimensionality to 95% variance  


## Analysis Summary  
- Chi-square tests to evaluate pre-/post-COVID shifts in categorical variables.  
- PCA to identify principal components aligned with pre-/post-COVID patterns.  
- K-means clustering to detect natural groupings in PCA space.  
- Visualizations supporting findings.  


## How to Run the Project  
- Open VS Code  
- Launch WSL 
- Download dataset   
- Install libraries  
- Open data_analysis.ipynb  
- Run cells in order  


## Notes  
- The dataset contains high missingness, which required extensive preprocessing for PCA and k‑means.  
- Chi‑square tests were robust to missingness.  
- Practical significance is more limited than raw percentages initially suggest.  
- COVID‑related reductions in law enforcement capacity may explain some observed decreases in documented cases.  

