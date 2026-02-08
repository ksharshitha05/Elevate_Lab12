# Elevate_Lab12

# Task 12: Customer Segmentation using KMeans

## 📌 Project Overview
This project implements **customer segmentation using the KMeans clustering algorithm** on the Mall Customer Segmentation dataset.  
The goal is to group customers based on their **annual income** and **spending behavior** to help businesses design targeted marketing strategies.

This task demonstrates the use of **unsupervised machine learning** for real-world business applications.

---

## 🎯 Objective
- Perform customer segmentation using KMeans clustering
- Identify optimal number of clusters using the Elbow Method
- Visualize customer groups
- Save segmented data and plots automatically for reporting

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Scikit-learn  
  - Matplotlib  
  - Seaborn  
- **IDE:** VS Code / PyCharm  

---

## 📂 Dataset
**Mall Customer Segmentation Dataset**

Key Features Used:
- `Annual Income (k$)`
- `Spending Score (1-100)`

Note:  
`CustomerID` is excluded as it does not contribute to clustering.

---

## ⚙ Methodology
1. Load and inspect the dataset  
2. Select relevant features for clustering  
3. Apply **StandardScaler** to normalize data  
4. Use the **Elbow Method** to determine optimal number of clusters  
5. Train KMeans model with selected K value  
6. Assign cluster labels to customers  
7. Visualize clusters using scatter plots  
8. Save results automatically  

---

## 📊 Outputs Generated
All outputs are saved automatically in the `outputs/` folder:

- `elbow_plot.png` – Elbow Method graph  
- `cluster_visualization.png` – Customer cluster visualization  
- `segmented_customers.csv` – Final dataset with cluster labels  

---

## 📁 Project Structure

KMeans-Customer-Segmentation/
│
├── Mall_Customers.csv
├── kmeans_customer_segmentation.py
├── outputs/
│ ├── elbow_plot.png
│ ├── cluster_visualization.png
│ └── segmented_customers.csv
├── README.md
└── requirements.txt

#Outputs

<img width="1335" height="580" alt="Image" src="https://github.com/user-attachments/assets/99b1da5c-29d9-472c-9a68-aa4ed50250ac" />
<img width="896" height="589" alt="Image" src="https://github.com/user-attachments/assets/cf4d993c-2ed6-45df-9a35-5b600945fe83" />
<img width="835" height="581" alt="Image" src="https://github.com/user-attachments/assets/bb45da09-eb12-42eb-80d1-b53cf92392d3" />
