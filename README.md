# 🧠 Biochar_Stabilized_Resilient_Modulus

Resilient Modulus Prediction using Physics-Informed Machine Learning (PI-MS) for Biochar Stabilized Soil.

---

# Running the Application

## Method 1: With Python Environment

### 1. Place the following files in the same directory:

- app.py  
- PINN_MS_model.h5  
- physics_model.pkl  
- physics_stats.pkl  
- scaler_X1.pkl  
- scaler_X2.pkl  
- scaler_X3.pkl  
- Final_SHAP_Background.pkl  
- requirements.txt  

---

### 2. Open PowerShell

Press:
Win + R
type powershell
Press Enter

---

### 3. Navigate to the directory containing the files:
cd "Your downloaded path"

Example:
cd "D:\Biochar_Stabilized_Resilient_Modulus"

---

### 4. Run the application:
streamlit run app.py

---

### 5. Wait approximately 5–20 seconds  
(depending on your computer's performance)

The application will automatically open in your browser.

---

# Input Parameters

The GUI requires the following inputs:

- **w** — Moisture Content (%)  
- **gd** — Dry Unit Weight (kN/m³)  
- **NFT** — Number of Freeze-Thaw Cycles  
- **wPI** — Plasticity Index (%)  
- **sc** — Confining Stress (kPa)  
- **sd** — Deviator Stress (kPa)  

---

# Output

The system provides:

- Predicted **Resilient Modulus (MR)**  
- Strength Classification Gauge  
- SHAP Feature Contribution Plot  

---

# Note

- Ensure all model files (.pkl, .h5) are in the same folder  
- Use Python version **3.9–3.11**  
- First run may take slightly longer  

---

# About

This project presents a **Physics-Informed Machine Learning (PI-MS)** based GUI system for predicting the **Resilient Modulus (MR)** of **Biochar-Stabilized Soil** using laboratory-based soil parameters.

The system integrates:

- Machine Learning  
- Physics-Based Modeling  
- Explainable AI (SHAP)

for fast, reliable, and interpretable soil strength prediction.
