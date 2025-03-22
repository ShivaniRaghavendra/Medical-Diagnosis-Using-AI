# Medical-Diagnosis-Using-AI
AI-powered medical diagnosis system leveraging machine learning
### **Disease Prediction App**  
A **Streamlit-based web application** for predicting diseases like **Heart Disease, Parkinson’s Disease, Lung Cancer, Diabetes, and Hypo-Thyroid Disease** using **Machine Learning models**.  

---

## **Features**  
✔️ **User-friendly UI** with Streamlit  
✔️ **Predicts multiple diseases** based on user input  
✔️ **Trained ML models** for high accuracy  
✔️ **Interactive visualizations** with a background image  

---

## **Tech Stack**  
🟢 **Python** – ML models & backend  
🟢 **Streamlit** – Web UI  
🟢 **Pickle** – Loading pre-trained models  
🟢 **Machine Learning** – Trained on real-world datasets  

---

## **Installation**  
1️⃣ **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/disease-prediction-app.git  
   cd disease-prediction-app  
   ```  
2️⃣ **Install Dependencies**  
   ```bash
   pip install -r requirements.txt  
   ```  
3️⃣ **Run the Application**  
   ```bash
   streamlit run app.py  
   ```  

---

## **Diseases Supported**  
✅ **Heart Disease**  
✅ **Parkinson’s Disease**  
✅ **Hypo-Thyroid Disease**  
✅ **Lung Cancer**  
✅ **Diabetes**  

---

## **Patient Data (Input Features)**  

### **1. Diabetes Prediction**  
- **Number of Pregnancies**  
- **Glucose Level**  
- **Blood Pressure**  
- **Skin Thickness**  
- **Insulin Level**  
- **BMI (Body Mass Index)**  
- **Diabetes Pedigree Function**  
- **Age**  

### **2. Heart Disease Prediction**  
- **Age, Sex**  
- **Chest Pain Type (CP)**  
- **Resting Blood Pressure (trestbps)**  
- **Serum Cholesterol (chol)**  
- **Fasting Blood Sugar (fbs)**  
- **Resting Electrocardiographic Results (restecg)**  
- **Maximum Heart Rate (thalach)**  
- **Exercise-Induced Angina (exang)**  
- **ST Depression (oldpeak)**  
- **Slope of the Peak Exercise ST Segment (slope)**  
- **Major Vessels (ca)**  
- **Thalassemia (thal)**  

### **3. Parkinson’s Disease Prediction**  
- **MDVP: Fo(Hz), MDVP: Fhi(Hz), MDVP: Flo(Hz)**  
- **MDVP: Jitter(%), MDVP: Jitter(Abs)**  
- **MDVP: RAP, MDVP: PPQ, Jitter: DDP**  
- **MDVP: Shimmer, MDVP: Shimmer(dB)**  
- **Shimmer: APQ3, APQ5, APQ, Shimmer: DDA**  
- **NHR (Noise-to-Harmonics Ratio), HNR (Harmonics-to-Noise Ratio)**  
- **RPDE, DFA, Spread1, Spread2, D2, PPE**  

### **4. Lung Cancer Prediction**  
- **Gender, Age**  
- **Smoking, Yellow Fingers**  
- **Anxiety, Peer Pressure**  
- **Chronic Disease, Fatigue**  
- **Allergy, Wheezing**  
- **Alcohol Consumption, Coughing**  
- **Shortness of Breath, Swallowing Difficulty**  
- **Chest Pain**  

### **5. Hypo-Thyroid Disease Prediction**  
- **Age, Sex**  
- **On Thyroxine**  
- **TSH Level**  
- **T3 Measured, T3 Level**  
- **TT4 Level**  

