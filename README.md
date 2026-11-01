# E-Commerce Customer Segmentation

## 📌 Project Overview

This project focuses on segmenting e-commerce customers based on their purchasing behaviour using unsupervised machine learning techniques. Customer segmentation helps businesses understand different types of customers and develop targeted marketing strategies.

The project applies **K-Means Clustering** and **DBSCAN** and uses **PCA** and **t-SNE** for dimensionality reduction and visualization.

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA).
- Handle missing values and prepare the dataset.
- Create RFM features: Recency, Frequency, and Monetary.
- Scale numerical features before clustering.
- Apply K-Means and DBSCAN clustering algorithms.
- Use PCA and t-SNE to visualize customer segments.
- Evaluate and compare clustering results.
- Develop actionable marketing personas for different customer groups.

## 📊 Dataset

The project uses an online retail/customer marketing dataset containing customer purchase information.

The RFM features represent:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer makes purchases.
- **Monetary:** How much money a customer spends.

These features help identify customer purchasing patterns and value.

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

1. Data loading and exploration
2. Data cleaning and missing-value treatment
3. RFM feature engineering
4. Feature scaling using StandardScaler
5. K-Means clustering and cluster selection
6. DBSCAN clustering
7. Dimensionality reduction using PCA
8. Cluster visualization using t-SNE
9. Evaluation using the Silhouette Score, where applicable
10. Customer segment interpretation and marketing recommendations

## 📈 Algorithms Used

### K-Means Clustering

K-Means groups customers into a predefined number of clusters based on their similarity. The Elbow Method and Silhouette Score can help evaluate suitable cluster configurations.

### DBSCAN

DBSCAN groups closely packed data points and identifies noise or outliers. Unlike K-Means, it does not require specifying the number of clusters in advance.

### PCA

Principal Component Analysis reduces the number of dimensions while retaining as much variance as possible. It can help visualize high-dimensional customer data.

### t-SNE

t-SNE projects high-dimensional data into a lower-dimensional space, making local patterns and potential clusters easier to visualize.

## 💡 Marketing Applications

Customer segments can help businesses:

- Reward high-value and loyal customers.
- Offer personalized discounts to occasional buyers.
- Re-engage customers who have not purchased recently.
- Develop targeted campaigns based on purchasing behaviour.
- Allocate marketing resources more effectively.

Final customer personas should be assigned based on the actual cluster statistics obtained from the notebook.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Place the dataset in the appropriate location.
4. Open `Customer_Segmentation_CaseStudy.ipynb` in Jupyter Notebook.
5. Update the dataset path if required.
6. Run all notebook cells sequentially.

## 📁 Project Structure

```text
Customer-Segmentation/
├── Customer_Segmentation_CaseStudy.ipynb
├── README.md
├── requirements.txt
├── data/
└── results/
```

## ✅ Expected Outcome

The project aims to identify meaningful customer segments, compare K-Means and DBSCAN, visualize the resulting patterns, and translate the findings into practical marketing strategies.

## 👩‍💻 Author

**Vaishali Singh**

B.Tech — Computer Science and Engineering (AI & ML)
