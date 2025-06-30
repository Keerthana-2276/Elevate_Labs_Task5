# 🫀 Heart Disease Classification with Decision Tree and Random Forest

This project demonstrates how to use **Decision Tree** and **Random Forest** classifiers to predict the presence of heart disease based on clinical features.

## 📁 Dataset

A sample dataset of heart disease indicators with features such as age, sex, cholesterol levels, blood pressure, etc.

| Feature      | Description                                      |
|--------------|--------------------------------------------------|
| age          | Age of the patient                               |
| sex          | Gender (1 = male, 0 = female)                    |
| cp           | Chest pain type (0–3)                            |
| trestbps     | Resting blood pressure                           |
| chol         | Serum cholesterol (mg/dl)                        |
| fbs          | Fasting blood sugar > 120 mg/dl (1 = true)       |
| restecg      | Resting electrocardiographic results             |
| thalach      | Maximum heart rate achieved                      |
| exang        | Exercise induced angina (1 = yes)                |
| oldpeak      | ST depression induced by exercise                |
| slope        | Slope of the ST segment                          |
| ca           | Number of major vessels (0–3) colored by fluoroscopy |
| thal         | Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect) |
| target       | Diagnosis of heart disease (1 = disease, 0 = no disease) |

## 📌 Tasks Performed

1. **Upload and preprocess data**
2. **Train a Decision Tree Classifier**
3. **Visualize the Decision Tree**
4. **Analyze and control overfitting by adjusting max depth**
5. **Train a Random Forest Classifier**
6. **Interpret feature importances**
7. **Evaluate models using accuracy and classification report**
8. **Perform Cross-Validation**

## 🛠️ Tools & Libraries

- Python 3
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## 🧠 Model Comparison

| Model              | Accuracy (may vary) |
|--------------------|---------------------|
| Decision Tree      | ~70–90%             |
| Decision Tree (Limited Depth) | ~65–85%     |
| Random Forest      | ~80–95%             |

## 🧮 Feature Importance (Example)

thal → 0.25
ca → 0.20
oldpeak → 0.12
thalach → 0.10
chol → 0.08


## 📈 Visualization Example

- 📊 **Decision Tree Plot**
- 🔥 **Bar Chart of Feature Importances**

## 📎 How to Run in Colab

1. Upload `heart_data.csv` in Colab
2. Copy the code from [`decision_tree_random_forest.ipynb`](#)
3. Run cells to visualize and compare results

## 📚 License

MIT License – Feel free to use and modify!

---

