# 🌸 Iris K-Means Clustering

This project demonstrates **K-Means clustering**, an **unsupervised machine learning algorithm**, using the classic **Iris dataset**.  
The objective is to cluster iris flowers based on their features without using class labels during training.

---

## 📌 Project Overview

- **Algorithm:** K-Means Clustering  
- **Learning Type:** Unsupervised Learning  
- **Dataset:** Iris Dataset  
- **Language:** Python  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset Description

The Iris dataset contains **150 samples** with the following attributes:

| Feature | Description |
|-------|------------|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |
| Species | Actual flower species (used only for evaluation) |

> Note: The **species column is not used** while training the K-Means model.

---

## ⚙️ Project Workflow

1. Load the Iris dataset  
2. Perform Exploratory Data Analysis (EDA)  
3. Select numerical features  
4. Use **Elbow Method** to find optimal K  
5. Apply **K-Means clustering (K = 3)**  
6. Visualize clusters  
7. Compare clusters with actual species  

---

## 📊 Results

- Elbow Method suggests **K = 3** as the optimal number of clusters.
- K-Means clusters closely resemble the actual flower species.
- Clear separation is observed using petal features.

---

## 🧪 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/iris-kmeans-clustering.git
Go to the project directory

cd iris-kmeans-clustering


Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook iris_kmeans_clustering.ipynb

📁 Project Structure
iris-kmeans-clustering/
│
├── iris.data
├── iris.names
├── iris_kmeans_clustering.ipynb
├── README.md
└── requirements.txt

📌 Key Learnings

Basics of unsupervised learning

Working of K-Means algorithm

Choosing optimal clusters using Elbow Method

Visualizing and interpreting clusters

👨‍🎓 Author

Devendra Kushwah
