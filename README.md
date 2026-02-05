# Customer Segmentation using K-Means, Hierarchical Clustering, and RFM Analysis

## 📑 About the Project

This project performs **customer segmentation** using K-Means clustering, Hierarchical clustering, and RFM (Recency, Frequency, Monetary) analysis. The objective is to group customers based on their purchasing behaviour to aid targeted marketing strategies and personalised offers.

---

## 📂 Table of Contents

- [About the Project](#-about-the-project)
- [Technologies Used](#-technologies-used)
- [Dataset](#-dataset)
- [RFM Analysis](#-rfm-analysis)
- [K-Means Clustering](#-k-means-clustering)
- [Hierarchical Clustering](#-hierarchical-clustering)
- [Results and Insights](#-results-and-insights)
- [Installation](#-installation)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 💻 Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

---

## 📊 Dataset

- **Dataset:** Mall Customer Segmentation Data
- **Features used:**
  - CustomerID
  - Gender
  - Age
  - Annual Income
  - Spending Score
    

---

## 🧮 RFM Analysis

**RFM analysis** was performed to segment customers based on:

- **Recency:** How recently a customer purchased.
- **Frequency:** How often a customer purchases.
- **Monetary:** How much money a customer spends.

Steps included:

1. Calculating RFM metrics for each customer.
2. Scoring each metric and creating RFM segments.
3. Identifying high-value customers for loyalty programs.

---

## 📈 K-Means Clustering

- **Why used:** To group customers into segments based on features such as Annual Income and Spending Score.
- **Optimal clusters:** Determined using the **Elbow Method**.
- **Visualisations:**
  - Scatter plots showing customer clusters.
  - Cluster centroids highlighted for clarity.

---

## 🌳 Hierarchical Clustering

- **Why used:** To compare results with K-Means clustering for better segmentation insights.
- **Approach:**
  - Dendrogram plotted to find optimal number of clusters.
  - Agglomerative clustering implemented for final segmentation.
- **Results:** Explained the formation of customer groups based on hierarchical linkage.

---

## 📝 Results and Insights

- Segmented customers into distinct groups:
  - **Cluster 1:** High income, high spending – premium customers.
  - **Cluster 2:** Low income, low spending – discount seekers.
  - (Add all your observed segments here)

**Business recommendations:**

- Offer loyalty programs to premium customers.
- Design targeted campaigns for medium-tier clusters.
- Provide discounts to convert low spending groups.

---

## ⚙️ Installation

Install required dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
