# 🧠 Customer Segmentation using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-KMeans-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

Customer segmentation is a powerful data-driven strategy used by businesses to divide customers into meaningful groups based on shared characteristics.

This project implements **K-Means Clustering**, an unsupervised Machine Learning algorithm, to analyze customer data and group them into distinct segments. These insights help businesses improve **marketing strategies, customer engagement, and revenue generation**.

---

## 🎯 Problem Statement

In real-world scenarios, businesses often treat all customers similarly, leading to inefficient marketing and reduced profitability. Without segmentation, identifying valuable customers and targeting them effectively becomes difficult.

---

## 🎯 Objective

* To segment customers into distinct groups using Machine Learning
* To analyze customer behavior based on income and spending patterns
* To derive actionable insights for targeted marketing

---

## 📊 Dataset Description

The dataset used in this project contains customer information typically found in retail businesses.

### Features:

* `CustomerID` – Unique identifier
* `Gender` – Male/Female
* `Age` – Customer age
* `Annual Income (k$)` – Yearly income
* `Spending Score (1-100)` – Customer spending behavior

📁 Dataset file: `data/mall_customers.csv`

---

## 🛠️ Technologies Used

* **Programming Language:** Python 🐍
* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## ⚙️ Methodology

### 🔹 1. Data Preprocessing

* Removed unnecessary columns (CustomerID)
* Selected relevant features (Income & Spending Score)
* Checked for missing values

---

### 🔹 2. Exploratory Data Analysis (EDA)

* Visualized data distribution
* Analyzed relationships between variables
* Identified patterns and trends

---

### 🔹 3. Optimal Cluster Selection

* Applied **Elbow Method**
* Determined optimal value of K (number of clusters)

📍 Suggested Image Path:

```
images/elbow_method.png
```

---

### 🔹 4. Model Building

* Applied **K-Means Clustering Algorithm**
* Assigned cluster labels to each customer

---

### 🔹 5. Visualization

* Plotted clusters using scatter plots
* Highlighted centroids for better understanding

📍 Suggested Image Path:

```
images/customer_clusters.png
```

---

## 📈 Results & Insights

The model successfully segmented customers into **5 distinct clusters**:

| Cluster Type               | Description        |
| -------------------------- | ------------------ |
| High Income, High Spending | Premium customers  |
| Low Income, Low Spending   | Budget customers   |
| High Income, Low Spending  | Target customers   |
| Low Income, High Spending  | Impulsive buyers   |
| Average Group              | Moderate customers |

### 📌 Key Insights:

* Businesses should focus on **high-income low-spending customers** for growth
* Premium customers can be targeted for loyalty programs
* Marketing strategies can be personalized for each segment

---

## 📊 Visualizations

### 🔹 Elbow Method

Determines optimal number of clusters

```
images/elbow_method.png
```

---

### 🔹 Customer Segmentation Plot

Shows clustered customers with centroids

```
images/customer_clusters.png
```

---

### 🔹 Data Distribution

Helps understand feature spread

```
images/data_distribution.png
```

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Dhruvilllll/Customer-Segmentation.git
cd Customer-Segmentation
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run the Project

```bash
python main.py
```

---

## 📁 Project Structure

```
Customer-Segmentation/
│
├── data/
│   └── mall_customers.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── images/
│   ├── elbow_method.png
│   ├── customer_clusters.png
│   └── data_distribution.png
│
├── main.py
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

* Implement advanced clustering techniques (DBSCAN, Hierarchical Clustering)
* Build an interactive dashboard using Streamlit
* Deploy the model as a web application
* Add real-time customer segmentation

---

## 📸 Suggested Screenshots to Add

To improve presentation, include:

1. ✅ Elbow Method Graph
2. ✅ Cluster Visualization Plot
3. ✅ Dataset with Cluster Labels
4. ✅ Data Distribution Graphs

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit pull requests.

---

## 📬 Contact

**Dhruvil Malvania**
B.Tech Computer Science (Data Science Enthusiast)

📧 Connect via GitHub:
https://github.com/Dhruvilllll

---

## ⭐ If you found this project useful, consider giving it a star!
