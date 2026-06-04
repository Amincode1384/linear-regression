# E-commerce Customer Spending Prediction

A simple machine learning project that uses customer data to predict **Yearly Amount Spent** using **Linear Regression**.

This project is designed for beginners who want to learn how a real machine learning workflow works from start to finish.

---

## About the Project

Have you ever wondered how companies estimate customer value?

In this project, I built a Linear Regression model that analyzes customer behavior and predicts how much a customer is likely to spend annually.

The project walks through the complete machine learning pipeline, making it easy for beginners to understand and follow.

---

## Features

✅ Data Loading and Cleaning

✅ Exploratory Data Analysis (EDA)

✅ Data Visualization

✅ Train/Test Split

✅ Linear Regression Model Training

✅ Prediction Generation

✅ Model Evaluation

✅ Model Saving for Future Use

---

## Dataset Information

The dataset contains information about e-commerce customers, including:

- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (Target Variable)

The goal is to predict the **Yearly Amount Spent** based on customer behavior.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Machine Learning Workflow

### Step 1: Load the Dataset

Import customer data into Python using Pandas.

### Step 2: Explore the Data

Understand the structure, columns, and relationships between variables.

### Step 3: Visualize the Data

Create plots to identify patterns and correlations.

### Step 4: Prepare Features

Select input variables and define the target variable.

### Step 5: Split the Dataset

Divide the dataset into training and testing sets.

### Step 6: Train the Model

Fit a Linear Regression model using the training data.

### Step 7: Make Predictions

Generate predictions on unseen test data.

### Step 8: Evaluate Performance

Measure model accuracy using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Step 9: Save the Model

Store the trained model as a `.pkl` file for future use.

---

## Project Structure

```text
├── project1.ipynb
├── Ecommerce Customers.csv
├── ecommerce_model.pkl
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

Move into the project directory:

```bash
cd your-repository-name
```

Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

## Running the Project

Open the notebook:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Run all cells from top to bottom.

---

## Example Use Case

Suppose a company wants to estimate future customer spending.

Instead of making assumptions, the trained model can analyze customer behavior and provide a data-driven prediction.

This helps businesses:

- Improve marketing decisions
- Increase customer retention
- Understand customer value
- Optimize business strategies

---

## Results

The model successfully learns the relationship between customer behavior and yearly spending.

It can then estimate spending for new customers based on their activity data.

---

## Beginner-Friendly Notes

If you're new to Machine Learning, try experimenting with:

- Different train-test split ratios
- Additional visualizations
- Other regression algorithms
- Feature engineering techniques

Small experiments are one of the fastest ways to learn.

---

## Future Improvements

- Add Polynomial Regression
- Compare multiple ML algorithms
- Build a Streamlit web application
- Deploy the model online
- Add automated model evaluation reports

---

## Connect With Me

If you found this project useful, consider:

⭐ Starring the repository

🍴 Forking the project

👨‍💻 Checking out my other Machine Learning projects

Feedback and suggestions are always welcome!

---

## License

This project is created for educational and learning purposes.
