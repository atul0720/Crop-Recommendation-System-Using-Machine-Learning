# Crop-Recommendation-System-Using-Machine-Learning
Agricultural productivity depends heavily on soil health. Key soil parameters such as Nitrogen (N), Phosphorous (P), Potassium (K), and pH value directly influence crop growth and yield.This project builds a multi-class machine learning classification system that predicts the most suitable crop based on soil nutrient measurements. The goal is to support data-driven agricultural decisions and improve farming outcomes using AI.

## 🎯Problem Statement
Given soil measurements:
- N – Nitrogen content ratio  
- P – Phosphorous content ratio  
- K – Potassium content ratio  
- pH – Soil pH value
Predict the optimal crop type for cultivation.
Each record in the dataset represents soil conditions of a field, and the target variable (crop) specifies the ideal crop for that soil profile.

## 📊 Dataset Description
**File:** `soil_measures.csv`

| Feature | Description |
|----------|-------------|
| N | Nitrogen content ratio |
| P | Phosphorous content ratio |
| K | Potassium content ratio |
| pH | Soil pH value |
| crop | Target variable (categorical crop type) |

This is a multi-class classification problem

## 🧠 Approach
### 1️⃣ Exploratory Data Analysis (EDA)
- Distribution of soil nutrients
- Class distribution analysis
- Correlation between features
- Outlier detection

### 2️⃣ Data Preprocessing
- Train-test split
- Feature scaling
- Label encoding (if required)

### 3️⃣ Model Development
Implemented and compared multiple classification models:
- Logistic Regression (Multinomial)
- Random Forest Classifier
- Support Vector Machine (SVM)
- Gradient Boosting (if applicable)

### 4️⃣ Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Precision, Recall, F1-score
- Cross-validation

### 5️⃣ Feature Importance Analysis
Identified the most impactful soil metric contributing to crop prediction performance.

## 🏆 Results
Successfully developed a high-performing multi-class classifier.
Compared multiple algorithms for performance optimization.
Identified key soil parameter influencing crop selection.

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📂 Project Structure

```bash
Crop-Recommendation-System-Using-Machine-Learning/
│
├── data/
│   └── soil_measures.csv
│
├── notebooks/
│   └── EDA_and_Modeling.ipynb
│
├── src/
│   └── model_training.py
│
├── requirements.txt
└── README.md
```

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
git clone https://github.com/your-username/Crop-Recommendation-System-Using-Machine-Learning.git
cd Crop-Recommendation-System-Using-Machine-Learning

### 2️⃣ Install Dependencies
pip install -r requirements.txt

### 3️⃣ Run the Notebook
Open:
notebooks/EDA_and_Modeling.ipynb

Or run the training script:

python src/model_training.py

## 🌍 Business Impact

This project demonstrates how Machine Learning can assist farmers in precision agriculture by:
- Reducing guesswork in crop selection
- Improving yield optimization
- Supporting sustainable farming practices
- Enabling data-driven agricultural planning

## 📜 License
This project is licensed under the MIT License.
