# Olympic-Medal-Analys
# 🏅 Olympic Medal Analysis using Data Mining (K-Means Clustering)

## 📌 Project Description

This project focuses on analyzing Olympic athlete data using **data mining techniques**, specifically **K-Means Clustering**, to discover hidden patterns among athletes based on their physical attributes.

The project was developed and executed using **Google Colab**, leveraging Python libraries for data processing, clustering, and visualization.

---

## 🎯 Objectives

* Analyze Olympic athlete dataset
* Perform data preprocessing and cleaning
* Apply **K-Means clustering algorithm**
* Evaluate clustering using **Silhouette Score**
* Visualize clusters and interpret patterns

---

## 📂 Dataset

* **Name:** Olympic Athlete Events Dataset
* **Source:** Kaggle
* **Format:** CSV

### 🔹 Features Used

* Age
* Height
* Weight

### 🔹 Additional Features (Not used for clustering)

* Name, Team, Sport, Event, Medal, Year, Season

---

## ⚙️ Technologies Used

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🔄 Project Workflow

1. **Data Collection**

   * Load dataset using Pandas

2. **Data Preprocessing**

   * Handle missing values
   * Remove outliers
   * Select numerical features
   * Apply feature scaling

3. **Model Building**

   * Apply **K-Means Clustering**

4. **Model Optimization**

   * Apply **PCA (Principal Component Analysis)**
   * Determine optimal number of clusters

5. **Performance Evaluation**

   * Silhouette Score

6. **Visualization**

   * Cluster scatter plots

---

## 📊 Results

* Data grouped into optimal clusters using K-Means
* Improved clustering using PCA and preprocessing
* Achieved **Silhouette Score ≈ 0.33 (initial)**
* Improved score after optimization

---

## 📈 Output

* Cluster visualization graph
* Cluster-wise average values
* Silhouette Score evaluation

---

## 🧠 Key Insights

* Athletes can be grouped based on physical characteristics
* Clustering reveals hidden patterns in Olympic data
* Useful for sports analytics and performance grouping

---

## 🚀 How to Run

1. Open **Google Colab**
2. Upload dataset:

   ```
   athlete_events.csv
   ```
3. Run all cells step-by-step

---

## 📁 Project Structure

```
📦 Olympic-Medal-Analysis
 ┣ 📜 athlete_events.csv
 ┣ 📜 olympic_analysis.ipynb
 ┗ 📜 README.md
```

---

## ⚠️ Notes

* Only numerical features are used for clustering
* Categorical data is excluded to avoid errors
* Dataset contains missing values handled during preprocessing

---

## 🔮 Future Scope

* Include more features like country and sport
* Apply advanced clustering algorithms
* Build prediction models
* Develop a web-based dashboard

---

## 👨‍💻 Authors

* Ch. Raghu Veera Reddy
* J. Venkata Sai
* Y. Mani
* B. Sushmanth

---
