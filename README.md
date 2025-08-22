🌸 Iris Dataset EDA
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the famous Iris dataset.
The dataset contains measurements of iris flowers (sepal length, sepal width, petal length, petal width) across 3 species: setosa, versicolor, and virginica.
The objective of this project is to practice:
Loading and inspecting datasets with pandas
Generating descriptive statistics
Visualizing data with matplotlib and seaborn
Identifying patterns and outliers in the dataset

📂 Dataset
Source: Seaborn’s built-in Iris dataset
Shape: 150 samples × 5 columns
Features:
sepal_length
sepal_width
petal_length
petal_width
species (target class)

🛠️ Steps Performed
Data Loading
Loaded dataset with sns.load_dataset("iris")
Inspected shape, column names, first rows
Data Exploration
.info() to view datatypes and nulls
.describe() for summary statistics

Visualization
Scatter plot: Feature relationships (Sepal Length vs Petal Length)
Histograms: Feature distributions
Boxplots: Outlier detection and species comparison

📊 Key Insights
Petal length and petal width clearly separate the three species.
Setosa is distinctly smaller in petal dimensions compared to the other two species.
Versicolor and Virginica overlap slightly, making classification trickier.
Boxplots highlight variability in sepal width

🚀 How to Run
# Clone repo
git clone https://github.com/yourusername/iris-eda.git
cd iris-eda
# Open notebook
jupyter notebook iris_eda.ipynb

📌 Skills Practiced
Data Loading & Inspection (pandas)
Summary Statistics
Visualization with Seaborn & Matplotlib
Outlier Detection

📈 Next Steps
Apply classification models (Logistic Regression, Decision Trees, etc.)
Compare performance of different ML algorithms on this dataset.

✨ Author: Taimour Mushtaq
