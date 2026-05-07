# 📌 Task 11 – Principal Component Analysis (PCA)

## 🎯 Objective
The goal of this task is to apply **Principal Component Analysis (PCA)** on the Wine dataset to reduce dimensionality and visualize high-dimensional data in 2D.

---

## 📂 Dataset
**Wine Dataset**

Features used in the dataset:

- Alcohol  
- Malic_Acid  
- Ash  
- Ash_Alcanity  
- Magnesium  
- Total_Phenols  
- Flavanoids  
- Nonflavanoid_Phenols  
- Proanthocyanins  
- Color_Intensity  
- Hue  
- OD280  
- Proline  
- Target (Wine Class)

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔬 Steps Performed

### 1️⃣ Data Loading
Loaded the Wine dataset using **Pandas**.

### 2️⃣ Data Preprocessing
Separated the dataset into:
- Feature variables (X)
- Target variable (y)

### 3️⃣ Feature Scaling
Used **StandardScaler** to standardize the dataset because PCA is variance-based and requires features to be on the same scale.

### 4️⃣ Applying PCA
Applied **Principal Component Analysis** to transform the original features into principal components.

### 5️⃣ Explained Variance Analysis
Generated a **Scree Plot** to understand how much variance each component captures.

### 6️⃣ Dimensionality Reduction
Reduced the dataset to **2 Principal Components**.

### 7️⃣ Data Visualization
Created a **2D scatter plot** to visualize the transformed dataset.

---

## 📊 Results
- PCA successfully reduced dataset dimensionality.
- The first two principal components captured most of the dataset variance.
- The transformed data is easy to visualize and analyze.

-<img width="1919" height="1022" alt="task11 1" src="https://github.com/user-attachments/assets/702bf4fe-d261-4b87-a702-a68cd5d78945" />
-<img width="1918" height="1020" alt="task11 2" src="https://github.com/user-attachments/assets/d98ec309-0ffe-4008-a549-05538852e681" />
-<img width="1919" height="1010" alt="task11 3" src="https://github.com/user-attachments/assets/19642545-1b4b-412c-8eb8-90e579b99d3e" />
-<img width="1919" height="1026" alt="task11 4" src="https://github.com/user-attachments/assets/fa9645e9-9657-48bc-b331-ba75f2c0effa" />


---

## 🎓 Key Learnings
- PCA reduces the complexity of high-dimensional data.
- Removes multicollinearity between features.
- Improves machine learning performance.
- Helps visualize complex datasets.

---

## 📁 Project Structure
