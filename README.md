# This project leverages machine learning to determine if a tumor is benign or malignant using diagnostic measurements. The model is trained on the well-known Breast Cancer Wisconsin dataset, which is readily available in scikit-learn.
# 📁 Project Structure
bash
Copy
Edit
.
├── Breast_Cancer_Prediction.ipynb     # Exploratory Data Analysis & Model Building
├── app.py                             # Streamlit Web App
├── breast_cancer_knn.pkl              # Saved KNN model
├── breast_cancer_model.pkl            # Saved primary ML model
├── scaler.pkl                         # Saved scaler object for preprocessing
├── requirement.txt                    # List of dependencies
└── README.md                          # Project documentation
# 🔍 Dataset
Source: Scikit-learn Breast Cancer Dataset

Features: 30 numeric features representing characteristics of cell nuclei in digitized breast mass images.

Target: Binary classification – Malignant (1) or Benign (0)

# 🧠 Model Building
Conducted EDA, feature scaling, and model selection using methods like:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

The best model is saved as breast_cancer_model.pkl.

# 🚀 Streamlit Web App
Run the app with:

```bash
streamlit run app.py
```

Inputs include radius mean, texture mean, perimeter mean, area mean, etc.

Output predicts if the tumor is Benign or Malignant.

# 📦 Requirements
Install dependencies with:

```bash
pip install -r requirement.txt
```

# ✅ How to Use
Clone the repository:

```bash
git clone https://github.com/Ayush9227/Breast-Cancer-Prediction.git
cd Breast-Cancer-Prediction
```

Install dependencies, then run the app:

```bash
streamlit run app.py
```

Input values to get real-time predictions!
