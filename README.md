# 🎗️ Cancer Classification using Machine Learning


> An end-to-end Machine Learning pipeline for cancer patient classification using biomedical data — from exploratory analysis to a live deployed web application.

---

## 🌐 Live Demo

👉 **[Launch the Streamlit App](https://cancer-project-machine-learning.streamlit.app/)**

---

## 🎥 Demo Video

📽️ **[Watch the Project Presentation](https://canva.link/o2it46wakfeojmv)**

> The presentation walks through the project objectives, data analysis, model results, and a live demo of the application.

---

## 📋 Table of Contents

- [Project Description](#-project-description)
- [Dataset](#-dataset)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Machine Learning Models](#-machine-learning-models)
- [Results](#-results)
- [Tech Stack](#-tech-stack)
- [How to Run](#-how-to-run)
- [Project Structure](#-project-structure)
- [Team Members](#-team-members)

---

## 📖 Project Description

This project presents a complete **end-to-end Machine Learning pipeline** for cancer classification using real-world biomedical data collected from global cancer patients (2015–2024).

It demonstrates how **data science and AI techniques** can support **early cancer detection**, improving clinical decision-making in healthcare.

**Key components:**
- Thorough data preprocessing and feature engineering
- Exploratory Data Analysis (EDA) with visualizations
- Training and comparing multiple ML classification models
- Evaluation using standard metrics (Accuracy, Precision, Recall, F1-Score)
- Interactive Streamlit web application for real-time predictions

---

## 📊 Dataset

| Field | Details |
|-------|---------|
| **File** | `global_cancer_patients_2015_2024.csv` |
| **Source** | Included in this repository |
| **Original Source** | [Kaggle – Global Cancer Patients 2015–2024](https://www.kaggle.com/datasets/zahidmughal2343/global-cancer-patients-2015-2024)  |
| **Coverage** | Global cancer patient records, 2015–2024 |
| **Features** | Biomedical and demographic attributes related to cancer diagnosis |

 

---

## 🔍 Exploratory Data Analysis

The EDA phase (in `cancer_ml_project.ipynb`) covers:

- Feature distributions and histograms
- Correlation heatmaps
- Outlier detection using box plots
- Class balance inspection
- Key statistical summaries

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and evaluated:

| Model | Description |
|-------|-------------|
| **Logistic Regression** | Baseline linear classifier |
| **Random Forest** | Ensemble of decision trees |
| **XGBoost** | Gradient boosting framework |

Models were selected, tuned, and saved as `.pkl` files for use in the web application.

---

## 📈 Results

Models were evaluated using the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

> 📌 Detailed results, confusion matrices, and comparison charts can be found inside the [`cancer_ml_project.ipynb`](./cancer_ml_project.ipynb) notebook.

*(Add result screenshots here if available)*

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.8+ |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Model Serialization | Pickle |
| Web Application | Streamlit |
| Notebook | Jupyter Notebook |

---

## 🚀 How to Run

### Prerequisites

- Python 3.8 or higher
- pip

### 1. Clone the Repository

```bash
git clone https://github.com/merolaraafat16/Machine-Learning-Project.git
cd Machine-Learning-Project
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook (for model training & EDA)

```bash
jupyter notebook cancer_ml_project.ipynb
```

### 4. Run the Streamlit App (for live predictions)

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`

---

## 📁 Project Structure

```
Machine-Learning-Project/
│
├── cancer_ml_project.ipynb     # Main notebook: EDA, training, evaluation
├── app.py                      # Streamlit web application
├── model.pkl                   # Saved trained ML model
├── scaler.pkl                  # Saved feature scaler
├── label_encoder.pkl           # Saved label encoder
├── feature_names.pkl           # Saved feature names
├── global_cancer_patients_2015_2024.csv  # Dataset
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## 👤 Author

| Name | Email |
|------| ----- |
| Merola Raafat | M.2307@nu.edu.eg |



---

## 📝 Additional Notes

- The pre-trained model (`model.pkl`), scaler, encoder, and feature names are included in the repo, so you can run the Streamlit app **without retraining**.
- To retrain the model from scratch, run all cells in `cancer_ml_project.ipynb`.
- The live app is hosted on Streamlit Community Cloud and accessible at the link above.

---

*For questions or issues, please open a GitHub Issue in this repository.*
