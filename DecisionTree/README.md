# 🌳 Decision Tree Classifier — Breast Cancer Diagnosis

A complete, end-to-end notebook that trains and interprets a **Decision Tree Classifier** for breast-cancer diagnosis using a tabular dataset. It covers data inspection, model training, evaluation (report + confusion matrix), **tree visualization**, **feature importance**, correlations, and even a **per-sample decision path** to peek inside how the model makes predictions.

---

## ✨ Key Features
- 🧭 **Data Overview**: `head()`, `info()`, `describe()`, and missing-value checks  
- 🔀 **Train/Test Split**: Reproducible splits with `train_test_split`  
- 🤖 **Model**: `DecisionTreeClassifier()` fitted on engineered features  
- 📈 **Evaluation**: Accuracy score, **classification report**, **confusion matrix**  
- 🌳 **Model Explainability**:
  - Full **tree plot** (`sklearn.tree.plot_tree`)
  - **Top-k feature importance** bar chart
  - **Decision path** for a specific sample
- 🔎 **EDA Visuals**: Class distribution and feature-correlation heatmap

---

## 🚀 Getting Started
Open and run the notebook directly in **Google Colab**.  
You will be able to view the **entire source code**, perform training, and see **visualizations of the outputs** interactively.  

🔗 **Colab:** [Decision Tree – Breast Cancer Diagnosis](https://colab.research.google.com/drive/1ldotXwz_3VF7s2480nn8e_vJCzPwE0l_?usp=drive_link)


---

## 🧩 Dataset Assumptions
- Target column: **`diagnosis`** (e.g., classes `M`/`B`)  
- Features: all other numeric columns (dropped via `df.drop('diagnosis', axis=1)`)

If your CSV has different column names, update the code where `x` and `y` are defined.

---

## 📊 Results You’ll See
- **Model Score** on the test set  
- **Classification Report** (precision, recall, F1, support)  
- **Confusion Matrix** (plotted with `ConfusionMatrixDisplay`)  
- **Top 10 Feature Importances**  
- **Decision Tree Diagram** (colored, rounded nodes, feature/threshold at each split)  
- **Decision Path** indices for a chosen test sample

---

## 🖼️ Visualizations Included
- 📦 Class distribution (bar chart)  
- 🔥 Correlation heatmap for features  
- 🌳 Full decision tree plot  
- ⭐ Top-k feature importance (horizontal bar chart)  
- 🧪 Confusion matrix (blue colormap)

---

## 🛠️ Tech Stack
- Python 🐍, NumPy, Pandas  
- Scikit-Learn (`DecisionTreeClassifier`, metrics, plotting)  
- Matplotlib & Seaborn for visualization  
- Google Colab + Drive integration

---


