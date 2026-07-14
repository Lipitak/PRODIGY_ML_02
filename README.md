# Customer Segmentation using K-Means Clustering

## 📌 Overview
This project uses **K-Means Clustering** to segment mall customers into distinct groups based on their **Annual Income** and **Spending Score**. This helps businesses understand different customer types and design targeted marketing strategies for each segment.

This is **Task 2** of my Machine Learning Internship at **Prodigy InfoTech**.

## 📊 Dataset
- **Source**: [Kaggle - Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Records**: 200 customers
- **Features used**: Annual Income (k$), Spending Score (1-100)

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (KMeans)

## 🔍 Approach
1. Loaded and explored the dataset (checked for missing values, data types)
2. Selected relevant features — Annual Income and Spending Score
3. Used the **Elbow Method** to determine the optimal number of clusters (K=5)
4. Trained a K-Means model with K=5
5. Visualized the resulting clusters with a scatter plot
6. Interpreted each cluster's business meaning

## 📈 Results — Customer Segments

| Cluster | Avg Income (k$) | Avg Spending Score | Segment Name |
|---------|-----------------|---------------------|--------------|
| 0 | 55.3 | 49.5 | Average Customers |
| 1 | 86.5 | 82.1 | High Income, High Spending (VIP) |
| 2 | 25.7 | 79.4 | Low Income, High Spending (Impulsive) |
| 3 | 88.2 | 17.1 | High Income, Low Spending (Target for Growth) |
| 4 | 26.3 | 20.9 | Low Income, Low Spending (Budget) |

## 💡 Business Insight
These segments allow a business to design targeted strategies — for example, offering premium products to VIP customers, and personalized promotions to high-income-low-spending customers to increase their engagement.

## 👩‍💻 Author
Lipi | [LinkedIn](https://www.linkedin.com/in/lipi-tak/) | [GitHub](https://github.com/Lipitak)