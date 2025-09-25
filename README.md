# Transaction Fraud Detection (Unsupervised ML)

## Overview

This project applies unsupervised machine learning techniques to detect fraudulent transactions in credit card data. Using clustering algorithms, we identify patterns and anomalies that may indicate fraud, without relying on labeled data for training. The analysis is performed in Python using the Credit Card Fraud Detection dataset.

## Objectives

- Load and understand the dataset
- Clean and preprocess data (handle missing values, scale features)
- Perform Exploratory Data Analysis (EDA)
- Apply dimensionality reduction (PCA) for visualization
- Use clustering algorithms (K-Means, DBSCAN) for anomaly detection
- Visualize clusters and anomalies
- Profile segments and provide actionable insights

## Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** ~284,807 rows, 31 columns
- **Note:** Highly imbalanced (fraud rate ~0.17%)

## Project Structure

```
Transaction Fraud Detection/
├── week4project.ipynb   # Main analysis notebook
├── README.md            # Project documentation
```

## Key Steps

1. **Data Loading & Preprocessing:**
   - Load dataset from Kaggle or public URL
   - Handle missing values and scale features
2. **Exploratory Data Analysis (EDA):**
   - Visualize distributions and correlations
   - Calculate fraud rate
3. **Dimensionality Reduction:**
   - Use PCA for 2D visualization
4. **Clustering & Anomaly Detection:**
   - Apply K-Means and DBSCAN
   - Select optimal clusters using Elbow and Silhouette methods
   - Visualize clusters in PCA space
5. **Segment Profiling & Insights:**
   - Summarize cluster statistics
   - Identify segments with higher fraud rates
   - Provide business recommendations

## Technologies Used

- Python 3.11+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

## How to Run

1. **Install Python and Jupyter Notebook**
   - Download and install [Python](https://www.python.org/downloads/)
   - Install Jupyter: `pip install notebook`
2. **Install Required Packages**
   - Run: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. **Download the Dataset**
   - Download `creditcard.csv` from Kaggle and place it in the project folder (if not using the public URL)
4. **Open the Notebook**
   - Run: `jupyter notebook`
   - Open `week4project.ipynb` and run all cells

## How to Push to GitHub

1. **Initialize Git (if not already done)**
   - Open terminal in the project folder
   - Run: `git init`
2. **Add Files**
   - Run: `git add .`
3. **Commit Changes**
   - Run: `git commit -m "Initial commit: Transaction Fraud Detection project"`
4. **Create a New Repository on GitHub**
   - Go to [GitHub](https://github.com/) and create a new repository
5. **Add Remote and Push**
   - Run: `git remote add origin https://github.com/pranaynigam18/Transaction-Fraud-Detection.git`
   - Run: `git branch -M main`
   - Run: `git push -u origin main`

---

For any questions or improvements, feel free to open an issue or pull request.
