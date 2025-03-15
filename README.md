# 🧠 Brain Stroke Prediction using Machine Learning  

## 📌 Table of Contents  
- [Demo](#demo)  
- [Overview](#overview)  
- [Motivation](#motivation)  
- [Technical Aspect](#technical-aspect)  
- [Installation, Run & Deployment](#installation-run--deployment)  
- [Directory Structure](#directory-structure)  
- [To-Do & Bug / Feature Request](#to-do--bug--feature-request)  
- [Technologies Used](#technologies-used)  
- [Credits](#credits)  

---

## 🎥 Demo  
🔗 **Live Demo**: [Add your deployment link here]  
![Demo](https://your-demo-link.com/demo.gif)  

---

## 📖 Overview  
This project predicts the **risk of brain stroke** based on various health factors such as **age, BMI, glucose level, hypertension, heart disease, and lifestyle habits** using machine learning models.  

💡 **Models Used**:  
✔ Logistic Regression  
✔ Decision Tree Classifier  
✔ Random Forest Classifier (**Best Performing Model**)  
✔ Gradient Boosting Classifier  

📊 **Evaluation Metrics**:  
✔ Accuracy  
✔ Precision  
✔ Recall  
✔ F1-Score  

---

## 🎯 Motivation  
Brain strokes are a **leading cause of disability and death worldwide**. Early detection can **help prevent severe health complications**. This project aims to:  
✔ Develop a **predictive model** for early stroke detection.  
✔ Assist **doctors and healthcare professionals** in risk assessment.  
✔ Provide **patients with awareness** regarding stroke risks.  

---

## ⚙️ Technical Aspect  
1️⃣ **Data Preprocessing**  
- Handling missing values  
- Encoding categorical variables (e.g., gender, work type, smoking status)  
- Feature scaling for continuous variables (age, BMI, glucose level)  

2️⃣ **Exploratory Data Analysis (EDA)**  
- **Distribution of stroke cases**  
- **Correlation heatmap of health factors**  
- **Effect of smoking and hypertension on stroke risk**  

3️⃣ **Model Training & Evaluation**  
- **Train-test split**  
- **Training Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting**  
- **Selecting the best model based on accuracy & precision**  

4️⃣ **Model Deployment using Streamlit**  
- **Interactive UI** where users can input their health parameters  
- **Real-time prediction** of stroke probability  

---

## ⚡ Installation, Run & Deployment  
```bash
# Install dependencies
pip install -r requirements.txt  

# Run the project
jupyter notebook brain_stroke(Classification).ipynb  

# Install Streamlit for deployment
pip install streamlit  

# Run Streamlit app
streamlit run app.py  


📂 Directory Structure
📦 Brain Stroke Classification  
 ┣ 📂 data  
 ┃ ┣ 📄 stroke_data.csv  
 ┣ 📂 models  
 ┃ ┣ 📄 stroke_prediction.pkl  
 ┣ 📂 scripts  
 ┃ ┣ 📄 brain_stroke(Classification).ipynb  
 ┣ 📂 streamlit_app  
 ┃ ┣ 📄 app.py  
 ┣ 📄 requirements.txt  
 ┣ 📄 README.md  
 ┣ 📄 LICENSE  


✅ To-Do & Bug / Feature Request
# To-Do  
✔ Deploy the model using Flask API  
✔ Implement feature selection for better accuracy  

# Bug / Feature Request  
If you find a bug or want to request a new feature, open an issue

🛠 Technologies Used 
✔ Scikit-Learn (Machine Learning)  
✔ Streamlit (Web App Framework)  
✔ Pandas (Data Analysis)  
✔ Matplotlib & Seaborn (Data Visualization)  
✔ Joblib (Model Saving)  

🙌 Credits
# Dataset:  
✔ Kaggle Brain Stroke Prediction Dataset  

# Contributors:  
✔ B. Sowjanya  
