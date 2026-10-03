
# 🔥 Calories Burn Prediction using Machine Learning

This project predicts the number of **calories burned during exercise** using
machine learning techniques. It uses personal and exercise-related features
to build an accurate regression model.

---

## 📌 Project Overview

Calories burned during physical activities depend on several factors such as:
- Age
- Gender
- Height
- Weight
- Exercise duration
- Heart rate
- Body temperature

This project uses these features to train a **machine learning regression model**
that predicts calorie expenditure effectively.

---

## 🗂 Dataset Information

The project uses two datasets:

- **calories.csv**  
  Contains calorie values burned by individuals.

- **exercise.csv**  
  Contains exercise-related information such as duration, heart rate, and body temperature.

Both datasets are merged and processed to create the final training dataset.

---

## 🔄 Project Workflow

Data Collection
↓
Data Preprocessing
↓
Feature Engineering
↓
Model Training
↓
Model Evaluation
↓
Prediction

yaml
Copy code

---

## 🧠 Machine Learning Approach

- Data preprocessing includes:
  - Handling categorical variables (e.g., Gender encoding)
  - Merging datasets
  - Feature selection

- Model used:
  - Regression-based machine learning model  
    (e.g., XGBoost / Random Forest)

- Evaluation metrics:
  - Mean Absolute Error (MAE)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📁 Project Structure

calories-prediction-ml/
│
├── Calories_burn_predictionProject.ipynb
│ ├── Import Libraries
│ ├── Load Dataset
│ ├── Data Understanding (shape, info)
│ ├── Data Cleaning & Preprocessing
│ ├── Exploratory Data Analysis (Graphs)
│ ├── Feature Engineering
│ ├── Model Training
│ ├── Model Evaluation
│ └── Conclusion
│
├── README.md
├── calories.csv
└── exercise.csv

---
## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd calories-prediction-ml
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Then open `Calories_burn_predictionProject.ipynb`.

📊 Results
The model successfully learns the relationship between exercise parameters
and calorie burn.

Visualization graphs help in understanding data distribution and model performance.

The trained model provides accurate calorie burn predictions.

🎯 Conclusion
This project demonstrates a complete machine learning workflow, from raw
data to prediction. It highlights good practices such as:

Data preprocessing

Clean project structure

Model evaluation

Proper documentation

👨‍💻 Author
Ankush Rana
Computer Science & Engineering (AI & ML)

⭐ Acknowledgements
Dataset source: Kaggle

Libraries: Scikit-learn, XGBoost

Inspiration: Health & Fitness Analytics