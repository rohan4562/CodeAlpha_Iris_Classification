# 🌸 Iris Flower Classification - Machine Learning Project

This is a simple but powerful machine learning project that classifies Iris flowers into three species based on their physical characteristics.

## 📌 Problem Statement

Given the measurements of an Iris flower:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

We aim to predict its **species** using machine learning techniques.  
The three possible species are:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

## 📂 Dataset

The dataset used is the famous [Iris Dataset](https://www.kaggle.com/datasets/saurabh00007/iriscsv), which contains 150 samples of flowers with 4 features each.

## 🧠 Machine Learning Approach

We used the **Decision Tree Classifier** from scikit-learn to build the prediction model.

### 🔧 Technologies & Libraries:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## 🔄 Workflow

1. **Data Loading:** Loaded Iris dataset from CSV.
2. **Data Cleaning:** Removed unnecessary columns (`Id`) and checked for missing values.
3. **Exploratory Data Analysis (EDA):** Visualized feature distributions using seaborn pairplots.
4. **Data Preprocessing:** Split the dataset into training and testing sets.
5. **Model Building:** Used Decision Tree Classifier to train the model.
6. **Model Evaluation:** Checked accuracy and classification report on test data.
7. **Visualization:** Created a confusion matrix heatmap to visualize prediction performance.

## 📈 Output

- Achieved **100%+ accuracy**
- Model performs well across all 3 classes
- Visualization confirms low misclassification



## 🚀 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
