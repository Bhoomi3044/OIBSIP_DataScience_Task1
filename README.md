# OIBSIP Data Science Task 1 – Iris Flower Classification

##  Objective
The Iris dataset is a classic in machine learning and statistics, used to classify flowers into three species: **Setosa**, **Versicolor**, and **Virginica**.  
This project aims to build and evaluate machine learning models to predict the species of an iris flower based on its **sepal** and **petal** measurements.

---

## Dataset Details

The dataset contains **150 samples** equally distributed among the 3 species. Each flower sample has the following features:

| Feature         | Description                     |
|----------------|---------------------------------|
| `sepal length` | Length of the sepal (in cm)     |
| `sepal width`  | Width of the sepal (in cm)      |
| `petal length` | Length of the petal (in cm)     |
| `petal width`  | Width of the petal (in cm)      |
| `species`      | Target class (Setosa, etc.)     |

---

## Steps Performed

### 1. Data Loading
- Used `sklearn.datasets.load_iris()` to import the dataset.
- Converted it to a Pandas DataFrame for easier analysis.

### 2. Exploratory Data Analysis (EDA)
- Used pairplots and heatmaps to visualize the relationship between features.
- Observed that **petal length** and **petal width** are the most distinguishing features.

### 3. Data Preprocessing
- Checked for missing values (none found).
- Encoded the target variable for modeling.

### 4. Model Training
Trained the following classification models:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**

Used `train_test_split` for 80-20 train-test split and trained models using `scikit-learn`.

### 5. Evaluation Metrics
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**

---

## Model Performance

-  **Accuracy**: ~96–100%
-  **Classification Report**: High precision, recall, and F1-scores across all three classes
-  **Confusion Matrix**: Very few misclassifications, especially for Setosa

## Results & Outcome
The KNN model performed exceptionally well on the Iris dataset with high accuracy.
Features like Petal Length and Petal Width are highly influential in classification.

---

## Visualizations

- **Pairplot**: Shows clear class separation especially in petal features.
- **Confusion Matrix**: For KNN and Decision Tree, all predictions matched the actual class.

---

## Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---




