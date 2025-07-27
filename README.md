# ❤️ Heart Disease Predictor using Logistic Regression

This project uses a Logistic Regression model to predict the likelihood of heart disease based on patient medical data. It is trained on a dataset provided in Excel format (`heart_disease_data.xls`) and includes preprocessing, training, evaluation, and prediction components.

---

## 📁 Dataset

- **File**: `heart_disease_data.xls`
- **Format**: Microsoft Excel
- **Contents**: Medical records with features relevant to heart disease diagnosis.
- Ensure the dataset has no missing or corrupted values before training the model.

---

## 🔍 Features Used (Example)

*(This will vary depending on your Excel columns — adjust accordingly):*

- `age` – Patient age  
- `sex` – Gender (1 = male, 0 = female)  
- `cp` – Chest pain type  
- `trestbps` – Resting blood pressure  
- `chol` – Serum cholesterol  
- `fbs` – Fasting blood sugar  
- `thalach` – Max heart rate achieved  
- `exang` – Exercise induced angina  
- `target` – Diagnosis (1 = heart disease, 0 = no heart disease)

---

## 🧠 Model Details

- **Algorithm**: Logistic Regression (binary classification)
- **Language**: Python 3.x
- **Libraries**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib` / `seaborn`
  - `xlrd` (for reading `.xls` files)

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-predictor.git
   cd heart-disease-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the model training script:
   ```bash
   python train_model.py
   ```

4. (Optional) Run predictions:
   ```bash
   python predict.py
   ```

---

## 📂 File Structure

```
heart-disease-predictor/
├── heart_disease_data.xls     # Input dataset
├── train_model.py             # Model training + evaluation
├── predict.py                 # Prediction script (optional)
├── model.pkl                  # Saved model
├── requirements.txt
└── README.md
```

---

## ✅ Outputs

- Trained logistic regression model (`model.pkl`)
- Accuracy, confusion matrix, and classification report
- Prediction results for new input samples

---

## 🛠️ Future Improvements

- Add model comparison with Random Forest / SVM
- Create a web interface using Flask or Streamlit
- Add batch prediction for uploaded datasets

---

## 📌 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

- UCI Heart Disease Dataset
- scikit-learn developers
- Contributors to open-source Python libraries
