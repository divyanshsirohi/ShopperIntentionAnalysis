# Online Shopping Intention Analysis

This project applies unsupervised learning techniques to analyze customer behavior on an e-commerce platform. Using K-Means clustering, the goal is to segment users based on session attributes and evaluate alignment with actual purchase outcomes.

## Dataset

- Source: [Kaggle - henrysue/online-shoppers-intention](https://www.kaggle.com/datasets/henrysue/online-shoppers-intention)
- Records: 12,330 user sessions
- Features: Session metrics such as Bounce Rates, Product-Related Duration, etc.
- Target: Revenue (True/False)

## Objectives

- Identify natural groupings in user behavior using K-Means clustering
- Visualize clusters based on selected features
- Evaluate cluster quality using Adjusted Rand Index and Confusion Matrix

## Approach

- Preprocess and encode data
- Use Elbow Method to select optimal number of clusters
- Apply K-Means clustering on selected features
- Compare predicted clusters to actual labels
- Visualize results

## Dependencies

- pandas
- matplotlib
- seaborn
- scikit-learn
- scikit-plot
- kagglehub

Install with:

```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter notebook:

```bash
jupyter notebook Online_Shopping_Intention_Analysis.ipynb
```
