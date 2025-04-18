# Skin_Disorder_ML_project
# Skin Disorder Classification using Machine Learning

## 📋 Project Overview

This project aims to classify different types of skin disorders using machine learning techniques. Leveraging a labeled dataset of dermatological conditions, this project involves preprocessing, exploratory data analysis, model building, evaluation, and visualization.

## 🧠 Problem Statement

Early and accurate diagnosis of skin diseases is critical for timely treatment. This project uses machine learning models to identify and classify skin disorders based on clinical features.

## 📂 Dataset

The dataset contains clinical attributes related to skin disorders. Each row represents a patient's clinical data, and the target is the skin disorder type. The dataset includes:

- 34 clinical features (like itching, scaling, erythema, etc.)
- A target column indicating one of six skin diseases:
  - Psoriasis
  - Seboreic Dermatitis
  - Lichen Planus
  - Pityriasis Rosea
  - Chronic Dermatitis
  - Pityriasis Rubra Pilaris
DATASET = <a href="https://github.com/Pavan-0156/Skin_Disorder_ML_project/blob/main/PRCP-1028-Skin-Disorder-Prediction-20220512T101734Z-001.zip">Dataset</a>
## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 🧪 ML Models Used

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## ✅ Results Summary

| Model                | Accuracy |
|---------------------|----------|
| Decision Tree        | ~96%     |
| Random Forest        | ~98%     |
| K-Nearest Neighbors  | ~97%     |
| Support Vector Machine | ~97%  |

> 🔍 Random Forest performed the best with the highest accuracy.

## 📈 Visualizations

- Correlation heatmap to understand feature relationships
- Confusion matrices for model comparison
- Accuracy bar plot

## 🚀 How to Run

1. Clone the repository
2. Open the notebook `Skin Disorder.ipynb` in Jupyter
3. Run all cells sequentially

## 💡 Future Improvements

- Hyperparameter tuning for better accuracy
- Integration with image-based dermatology datasets
- Deploy as a web application

## 🤝 Acknowledgements

Special thanks to the UCI Machine Learning Repository for the dermatology dataset.

---

Feel free to modify this file according to your personal style or project additions. Let me know if you'd like a `.md` file ready to upload or if you want help deploying this project on Streamlit or Flask!


