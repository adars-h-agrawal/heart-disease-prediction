# ❤️ Heart Disease Prediction

A **Streamlit web application** that predicts the risk of heart disease using a **K-Nearest Neighbors (KNN)** machine learning model.  
This project demonstrates end-to-end ML deployment: from dataset preparation → model training → saving preprocessing artifacts → interactive web app.

---

## 📌 Features
- User-friendly web interface built with **Streamlit**  
- Input form for patient details (age, sex, chest pain, cholesterol, etc.)  
- Data preprocessing (scaling + encoding) handled automatically  
- KNN classifier trained on the **Heart Disease dataset**  
- Real-time prediction with clear output:  
  - ✅ Low Risk of Heart Disease  
  - ⚠️ High Risk of Heart Disease  

---

## 📂 Project Structure
- `app.py` → Streamlit app for prediction  
- `heart.csv` → Dataset used for training  
- `heart.ipynb` → Jupyter Notebook for model training  
- `knn_heart_model.pkl` → Trained KNN model  
- `heart_scaler.pkl` → Scaler used for preprocessing  
- `heart_columns.pkl` → Column names used during training  

---

## ⚙️ Installation & Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/adars-h-agrawal/heart-disease-prediction.git
   cd heart-disease-prediction

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Run the Streamlit app:
   ```bash
   streamlit run app.py

---

**Author**: Adarsh Agrawal

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
