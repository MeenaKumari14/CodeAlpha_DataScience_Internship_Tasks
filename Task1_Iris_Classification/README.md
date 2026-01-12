# Task 1: Iris Flower Classification

##  Project Overview
This project is the first task of my Data Science internship at **CodeAlpha**. It involves building a Machine Learning model to classify Iris flowers into three distinct species: **Setosa, Versicolor, and Virginica**. The classification is based on four physical features: sepal length, sepal width, petal length, and petal width.

## Dataset Description
The Iris dataset is a classic in the machine learning community. It contains 150 records with 5 attributes:
- **Sepal Length (cm)**
- **Sepal Width (cm)**
- **Petal Length (cm)**
- **Petal Width (cm)**
- **Species:** (Target Variable)

##  Project Workflow

### 1. Exploratory Data Analysis (EDA)
To understand the relationships between features, I performed several visualizations:
- **Pairplots:** To observe the clusters formed by different species.
- **Violin Plots:** To see the distribution and density of each feature.
- **Correlation Heatmap:** Identified that **Petal Length** and **Petal Width** have the highest correlation with the target species, making them the most important features.

### 2. Data Preprocessing
- Checked for null values (the dataset was clean).
- Used **Label Encoding** to convert categorical species names into numerical format for the model.
- Split the data into **Training (80%)** and **Testing (20%)** sets to evaluate the model's performance on unseen data.

### 3. Model Building & Training
- **Algorithm:** Logistic Regression was chosen due to its efficiency in multi-class classification problems.
- The model was trained using the `Scikit-learn` library.

### 4. Evaluation Metrics
The model performed exceptionally well, achieving high scores across all metrics:
- **Accuracy Score:** 96.67%
- **Classification Report:** High precision and recall for all three species.
- **Confusion Matrix:** Confirmed that the model only misclassified a single instance during testing.

##  Key Insights
- **Iris-Setosa** is linearly separable from the other two species, making it the easiest to identify.
- **Petal dimensions** are much more reliable for classification than sepal dimensions.

##  Libraries Used
- **Pandas & NumPy**: For data handling and numerical operations.
- **Seaborn & Matplotlib**: For advanced data visualization.
- **Scikit-learn**: For model training, splitting data, and performance evaluation.
